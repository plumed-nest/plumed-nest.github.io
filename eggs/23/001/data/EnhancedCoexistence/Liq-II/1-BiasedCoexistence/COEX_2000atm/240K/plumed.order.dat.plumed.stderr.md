**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.order.dat   
Download: [zipped raw stdout](plumed.order.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.order.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label refcv : No environments have been found! Please specify a PDB file in the REFERENCE or in the REFERENCE_1, REFERENCE_2, etc keywords
[fv-az1487-606:69713] *** Process received signal ***
[fv-az1487-606:69713] Signal: Aborted (6)
[fv-az1487-606:69713] Signal code:  (-6)
[fv-az1487-606:69713] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f4e7ae42520]
[fv-az1487-606:69713] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f4e7ae969fc]
[fv-az1487-606:69713] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f4e7ae42476]
[fv-az1487-606:69713] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f4e7ae287f3]
[fv-az1487-606:69713] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f4e7b2a4f26]
[fv-az1487-606:69713] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f4e7b2b6d9c]
[fv-az1487-606:69713] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f4e7b2b6e07]
[fv-az1487-606:69713] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f4e7b2b70bb]
[fv-az1487-606:69713] [ 8] plumed(+0x12f48)[0x55bac4e13f48]
[fv-az1487-606:69713] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f4e7ae29d90]
[fv-az1487-606:69713] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f4e7ae29e40]
[fv-az1487-606:69713] [11] plumed(+0x131e5)[0x55bac4e141e5]
[fv-az1487-606:69713] *** End of error message ***
</pre>
{% endraw %}
