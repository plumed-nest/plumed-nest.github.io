**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label refcv : No environments have been found! Please specify a PDB file in the REFERENCE or in the REFERENCE_1, REFERENCE_2, etc keywords
[fv-az1487-606:69744] *** Process received signal ***
[fv-az1487-606:69744] Signal: Aborted (6)
[fv-az1487-606:69744] Signal code:  (-6)
[fv-az1487-606:69744] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f4c22442520]
[fv-az1487-606:69744] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f4c224969fc]
[fv-az1487-606:69744] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f4c22442476]
[fv-az1487-606:69744] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f4c224287f3]
[fv-az1487-606:69744] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f4c228a4f26]
[fv-az1487-606:69744] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f4c228b6d9c]
[fv-az1487-606:69744] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f4c228b6e07]
[fv-az1487-606:69744] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f4c228b70bb]
[fv-az1487-606:69744] [ 8] plumed(+0x12f48)[0x5600c5624f48]
[fv-az1487-606:69744] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f4c22429d90]
[fv-az1487-606:69744] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f4c22429e40]
[fv-az1487-606:69744] [11] plumed(+0x131e5)[0x5600c56251e5]
[fv-az1487-606:69744] *** End of error message ***
</pre>
{% endraw %}
