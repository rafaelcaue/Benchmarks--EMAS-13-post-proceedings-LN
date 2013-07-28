Actor-Agent-based-benchmark-for-communication
=============================================

These are the codes used in the paper Benchmarking Communication in Actor- and Agent-Based Languages. This is an extended version, using Akka instead of Scala Actors. All of the codes for Scenarios 1 and 2 are for the configuration N = 500 000. For the other configurations simply change the appropriate values for each code.

The benchmark script used is available at: http://shootout.alioth.debian.org/

PS. Don't forget to update Jason codes 'basedir' value at line 2 build.xml with a correct path to the base directory where that build.xml for that code is. Also update jasonJar at line 10 build.xml with a correct path to the jason.jar located on your Jason install folder.


For future benchmarks on agent oriented programming languages please refer to our website at: http://www.inf.pucrs.br/maop.benchmarking/
