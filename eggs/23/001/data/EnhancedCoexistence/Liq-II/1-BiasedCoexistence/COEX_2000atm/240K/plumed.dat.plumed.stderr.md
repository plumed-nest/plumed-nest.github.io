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
[fv-az1272-851:06379] *** Process received signal ***
[fv-az1272-851:06379] Signal: Aborted (6)
[fv-az1272-851:06379] Signal code:  (-6)
[fv-az1272-851:06379] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7ff12a842520]
[fv-az1272-851:06379] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7ff12a8969fc]
[fv-az1272-851:06379] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7ff12a842476]
[fv-az1272-851:06379] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7ff12a8287f3]
[fv-az1272-851:06379] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7ff12aca2b9e]
[fv-az1272-851:06379] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7ff12acae20c]
[fv-az1272-851:06379] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7ff12acae277]
[fv-az1272-851:06379] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7ff12acae52b]
[fv-az1272-851:06379] [ 8] plumed(+0x12f48)[0x55e1cb594f48]
[fv-az1272-851:06379] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7ff12a829d90]
[fv-az1272-851:06379] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7ff12a829e40]
[fv-az1272-851:06379] [11] plumed(+0x131e5)[0x55e1cb5951e5]
[fv-az1272-851:06379] *** End of error message ***
</pre>
{% endraw %}
