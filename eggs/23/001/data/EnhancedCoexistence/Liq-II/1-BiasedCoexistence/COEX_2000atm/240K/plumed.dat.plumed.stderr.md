**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label refcv : No environments have been found! Please specify a PDB file in the REFERENCE or in the REFERENCE_1, REFERENCE_2, etc keywords
[fv-az1487-606:69650] *** Process received signal ***
[fv-az1487-606:69650] Signal: Aborted (6)
[fv-az1487-606:69650] Signal code:  (-6)
[fv-az1487-606:69650] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f3dcda42520]
[fv-az1487-606:69650] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f3dcda969fc]
[fv-az1487-606:69650] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f3dcda42476]
[fv-az1487-606:69650] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f3dcda287f3]
[fv-az1487-606:69650] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f3dcdea4f26]
[fv-az1487-606:69650] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f3dcdeb6d9c]
[fv-az1487-606:69650] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f3dcdeb6e07]
[fv-az1487-606:69650] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f3dcdeb70bb]
[fv-az1487-606:69650] [ 8] plumed(+0x12f48)[0x5583e1365f48]
[fv-az1487-606:69650] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f3dcda29d90]
[fv-az1487-606:69650] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f3dcda29e40]
[fv-az1487-606:69650] [11] plumed(+0x131e5)[0x5583e13661e5]
[fv-az1487-606:69650] *** End of error message ***
</pre>
{% endraw %}
