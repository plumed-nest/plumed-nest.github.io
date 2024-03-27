**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.order.dat   
Download: [zipped raw stdout](plumed.order.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.order.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:302) void PLMD::Action::error(const string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[fv-az1487-606:69721] *** Process received signal ***
[fv-az1487-606:69721] Signal: Aborted (6)
[fv-az1487-606:69721] Signal code:  (-6)
[fv-az1487-606:69721] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fe7dec42520]
[fv-az1487-606:69721] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fe7dec969fc]
[fv-az1487-606:69721] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fe7dec42476]
[fv-az1487-606:69721] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fe7dec287f3]
[fv-az1487-606:69721] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fe7df0a4f26]
[fv-az1487-606:69721] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fe7df0b6d9c]
[fv-az1487-606:69721] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fe7df0b6e07]
[fv-az1487-606:69721] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fe7df0b70bb]
[fv-az1487-606:69721] [ 8] plumed_master(+0x12e7f)[0x560cbcafbe7f]
[fv-az1487-606:69721] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fe7dec29d90]
[fv-az1487-606:69721] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fe7dec29e40]
[fv-az1487-606:69721] [11] plumed_master(+0x13115)[0x560cbcafc115]
[fv-az1487-606:69721] *** End of error message ***
</pre>
{% endraw %}
