**Project ID:** [plumID:21.044]({{ '/' | absolute_url }}eggs/21/044/)  
Stderr for source:  driver.dat   
Download: [zipped raw stdout](driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/ActionShortcut.cpp:98) void PLMD::ActionShortcut::readInputLine(const string&, bool)
+++ assertion failed: keywords.componentHasCorrectType(".#!value", (av->copyOutput(0))->getRank(), (av->copyOutput(0))->hasDerivatives() )
documentation for type of value is incorrect
[fv-az802-461:06825] *** Process received signal ***
[fv-az802-461:06825] Signal: Aborted (6)
[fv-az802-461:06825] Signal code:  (-6)
[fv-az802-461:06825] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fa6bb842520]
[fv-az802-461:06825] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fa6bb8969fc]
[fv-az802-461:06825] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fa6bb842476]
[fv-az802-461:06825] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fa6bb8287f3]
[fv-az802-461:06825] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fa6bbca2b9e]
[fv-az802-461:06825] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fa6bbcae20c]
[fv-az802-461:06825] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fa6bbcae277]
[fv-az802-461:06825] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fa6bbcae52b]
[fv-az802-461:06825] [ 8] plumed_master(+0x14254)[0x55d55f299254]
[fv-az802-461:06825] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fa6bb829d90]
[fv-az802-461:06825] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fa6bb829e40]
[fv-az802-461:06825] [11] plumed_master(+0x14eb5)[0x55d55f299eb5]
[fv-az802-461:06825] *** End of error message ***
</pre>
{% endraw %}
