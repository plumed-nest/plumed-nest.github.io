**Project ID:** [plumID:21.011]({{ '/' | absolute_url }}eggs/21/011/)  
Stderr for source:  NaCl_at_graphite-cmumd/coordination-profiles.plmd   
Download: [zipped raw stdout](coordination-profiles.plmd.plumed_master.stdout.txt.zip) - [zipped raw stderr](coordination-profiles.plmd.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/ActionShortcut.cpp:98) void PLMD::ActionShortcut::readInputLine(const string&, bool)
+++ assertion failed: keywords.componentHasCorrectType(".#!value", (av->copyOutput(0))->getRank(), (av->copyOutput(0))->hasDerivatives() )
documentation for type of value is incorrect
[fv-az585-767:07853] *** Process received signal ***
[fv-az585-767:07853] Signal: Aborted (6)
[fv-az585-767:07853] Signal code:  (-6)
[fv-az585-767:07853] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f84f8e42520]
[fv-az585-767:07853] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f84f8e969fc]
[fv-az585-767:07853] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f84f8e42476]
[fv-az585-767:07853] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f84f8e287f3]
[fv-az585-767:07853] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f84f92a2b9e]
[fv-az585-767:07853] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f84f92ae20c]
[fv-az585-767:07853] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f84f92ae277]
[fv-az585-767:07853] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f84f92ae52b]
[fv-az585-767:07853] [ 8] plumed_master(+0x14254)[0x5653a3963254]
[fv-az585-767:07853] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f84f8e29d90]
[fv-az585-767:07853] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f84f8e29e40]
[fv-az585-767:07853] [11] plumed_master(+0x14eb5)[0x5653a3963eb5]
[fv-az585-767:07853] *** End of error message ***
</pre>
{% endraw %}
