**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX with label @s41 : missing SWITCH11 keyword
[fv-az1444-322:12503] *** Process received signal ***
[fv-az1444-322:12503] Signal: Aborted (6)
[fv-az1444-322:12503] Signal code:  (-6)
[fv-az1444-322:12503] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f59f1045330]
[fv-az1444-322:12503] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f59f109eb2c]
[fv-az1444-322:12503] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f59f104527e]
[fv-az1444-322:12503] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f59f10288ff]
[fv-az1444-322:12503] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f59f14a5ff5]
[fv-az1444-322:12503] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f59f14bb0da]
[fv-az1444-322:12503] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f59f14a5a55]
[fv-az1444-322:12503] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f59f14a5a6f]
[fv-az1444-322:12503] [ 8] plumed(+0x146dd)[0x56357ecf06dd]
[fv-az1444-322:12503] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f59f102a1ca]
[fv-az1444-322:12503] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f59f102a28b]
[fv-az1444-322:12503] [11] plumed(+0x15365)[0x56357ecf1365]
[fv-az1444-322:12503] *** End of error message ***
</pre>
{% endraw %}
