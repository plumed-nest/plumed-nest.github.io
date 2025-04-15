**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_GeTe.dat   
Download: [zipped raw stdout](plumed_GeTe.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_GeTe.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label cc_cmat : it was not possible to interpret atom name flq6
[fv-az1921-959:69582] *** Process received signal ***
[fv-az1921-959:69582] Signal: Aborted (6)
[fv-az1921-959:69582] Signal code:  (-6)
[fv-az1921-959:69582] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7ddec45330]
[fv-az1921-959:69582] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7ddec9eb2c]
[fv-az1921-959:69582] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7ddec4527e]
[fv-az1921-959:69582] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7ddec288ff]
[fv-az1921-959:69582] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7ddf0a5ff5]
[fv-az1921-959:69582] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7ddf0bb0da]
[fv-az1921-959:69582] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7ddf0a5a55]
[fv-az1921-959:69582] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7ddf0a5a6f]
[fv-az1921-959:69582] [ 8] plumed(+0x146dd)[0x55ae2d0a16dd]
[fv-az1921-959:69582] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7ddec2a1ca]
[fv-az1921-959:69582] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7ddec2a28b]
[fv-az1921-959:69582] [11] plumed(+0x15365)[0x55ae2d0a2365]
[fv-az1921-959:69582] *** End of error message ***
</pre>
{% endraw %}
