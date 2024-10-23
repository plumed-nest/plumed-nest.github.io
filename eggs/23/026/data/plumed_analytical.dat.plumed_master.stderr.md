**Project ID:** [plumID:23.026]({{ '/' | absolute_url }}eggs/23/026/)  
Stderr for source:  plumed_analytical.dat   
Download: [zipped raw stdout](plumed_analytical.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analytical.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/ActionShortcut.cpp:98) void PLMD::ActionShortcut::readInputLine(const string&, bool)
+++ assertion failed: keywords.componentHasCorrectType(".#!value", (av->copyOutput(0))->getRank(), (av->copyOutput(0))->hasDerivatives() )
documentation for type of value is incorrect
[fv-az1429-284:03894] *** Process received signal ***
[fv-az1429-284:03894] Signal: Aborted (6)
[fv-az1429-284:03894] Signal code:  (-6)
[fv-az1429-284:03894] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7efc6d642520]
[fv-az1429-284:03894] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7efc6d6969fc]
[fv-az1429-284:03894] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7efc6d642476]
[fv-az1429-284:03894] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7efc6d6287f3]
[fv-az1429-284:03894] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7efc6daa2b9e]
[fv-az1429-284:03894] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7efc6daae20c]
[fv-az1429-284:03894] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7efc6daae277]
[fv-az1429-284:03894] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7efc6daae52b]
[fv-az1429-284:03894] [ 8] plumed_master(+0x14254)[0x564cefea2254]
[fv-az1429-284:03894] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7efc6d629d90]
[fv-az1429-284:03894] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7efc6d629e40]
[fv-az1429-284:03894] [11] plumed_master(+0x14eb5)[0x564cefea2eb5]
[fv-az1429-284:03894] *** End of error message ***
</pre>
{% endraw %}
