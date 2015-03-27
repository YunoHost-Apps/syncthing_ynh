# syncthing_ynh


=================
TODO

- finaliser le script sysvinit pour se passer de runit
- mettre à jour et finaliser script upgrade
- mettre à jour et finaliser script remove


=================
Syncthing man

Usage:
  syncthing [options]

Options:
  -generate=""            Generate key and config in specified dir, then exit
  -gui-address=""         Override GUI address
  -gui-apikey=""          Override GUI API key
  -gui-authentication=""  Override GUI authentication; username:password
  -home=""                Set configuration directory
  -logflags="2"           Select information in log line prefix
  -no-browser             Do not start browser
  -no-restart             Do not restart; just exit
  -reset                  Prepare to resync from cluster
  -upgrade                Perform upgrade
  -upgrade-check          Check for available upgrade
  -upgrade-to=""          Force upgrade directly from specified URL
  -version                Show version


The default configuration directory is:

  ~/.config/syncthing


The -logflags value is a sum of the following:

   1  Date
   2  Time
   4  Microsecond time
   8  Long filename
  16  Short filename

I.e. to prefix each log line with date and time, set -logflags=3 (1 + 2 from
above). The value 0 is used to disable all of the above. The default is to
show time only (2).


Development Settings
--------------------

The following environment variables modify syncthing's behavior in ways that
are mostly useful for developers. Use with care.

 STGUIASSETS     Directory to load GUI assets from. Overrides compiled in assets.

 STTRACE         A comma separated string of facilities to trace. The valid
                 facility strings are:

                 - "beacon"   (the beacon package)
                 - "discover" (the discover package)
                 - "events"   (the events package)
                 - "files"    (the files package)
                 - "net"      (the main package; connections & network messages)
                 - "model"    (the model package)
                 - "scanner"  (the scanner package)
                 - "stats"    (the stats package)
                 - "upnp"     (the upnp package)
                 - "xdr"      (the xdr package)
                 - "all"      (all of the above)

 STPROFILER      Set to a listen address such as "127.0.0.1:9090" to start the
                 profiler with HTTP access.

 STCPUPROFILE    Write a CPU profile to cpu-$pid.pprof on exit.

 STHEAPPROFILE   Write heap profiles to heap-$pid-$timestamp.pprof each time
                 heap usage increases.

 STBLOCKPROFILE  Write block profiles to block-$pid-$timestamp.pprof every 20
                 seconds.

 STPERFSTATS     Write running performance statistics to perf-$pid.csv. Not
                 supported on Windows.

 STNOUPGRADE     Disable automatic upgrades.

 GOMAXPROCS      Set the maximum number of CPU cores to use. Defaults to all
                 available CPU cores.
