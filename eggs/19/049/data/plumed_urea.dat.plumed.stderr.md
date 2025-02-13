**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX with label @s41 : missing SWITCH11 keyword
[fv-az1280-696:14053] *** Process received signal ***
[fv-az1280-696:14053] Signal: Aborted (6)
[fv-az1280-696:14053] Signal code:  (-6)
[fv-az1280-696:14053] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f82e7645330]
[fv-az1280-696:14053] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f82e769eb2c]
[fv-az1280-696:14053] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f82e764527e]
[fv-az1280-696:14053] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f82e76288ff]
[fv-az1280-696:14053] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f82e7aa5ff5]
[fv-az1280-696:14053] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f82e7abb0da]
[fv-az1280-696:14053] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f82e7aa5a55]
[fv-az1280-696:14053] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f82e7aa5a6f]
[fv-az1280-696:14053] [ 8] plumed(+0x146dd)[0x55ec8e3886dd]
[fv-az1280-696:14053] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f82e762a1ca]
[fv-az1280-696:14053] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f82e762a28b]
[fv-az1280-696:14053] [11] plumed(+0x15365)[0x55ec8e389365]
[fv-az1280-696:14053] *** End of error message ***
</pre>
{% endraw %}
