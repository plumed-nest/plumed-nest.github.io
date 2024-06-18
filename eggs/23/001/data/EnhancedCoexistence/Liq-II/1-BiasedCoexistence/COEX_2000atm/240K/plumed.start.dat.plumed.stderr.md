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
[fv-az1272-851:06474] *** Process received signal ***
[fv-az1272-851:06474] Signal: Aborted (6)
[fv-az1272-851:06474] Signal code:  (-6)
[fv-az1272-851:06474] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f42cb642520]
[fv-az1272-851:06474] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f42cb6969fc]
[fv-az1272-851:06474] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f42cb642476]
[fv-az1272-851:06474] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f42cb6287f3]
[fv-az1272-851:06474] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f42cbaa2b9e]
[fv-az1272-851:06474] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f42cbaae20c]
[fv-az1272-851:06474] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f42cbaae277]
[fv-az1272-851:06474] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f42cbaae52b]
[fv-az1272-851:06474] [ 8] plumed(+0x12f48)[0x55a18e842f48]
[fv-az1272-851:06474] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f42cb629d90]
[fv-az1272-851:06474] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f42cb629e40]
[fv-az1272-851:06474] [11] plumed(+0x131e5)[0x55a18e8431e5]
[fv-az1272-851:06474] *** End of error message ***
</pre>
{% endraw %}
