**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_GeTe.dat   
Download: [zipped raw stdout](plumed_GeTe.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_GeTe.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label cc_cmat : it was not possible to interpret atom name flq6
[fv-az1280-696:13960] *** Process received signal ***
[fv-az1280-696:13960] Signal: Aborted (6)
[fv-az1280-696:13960] Signal code:  (-6)
[fv-az1280-696:13960] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8fc0a45330]
[fv-az1280-696:13960] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8fc0a9eb2c]
[fv-az1280-696:13960] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8fc0a4527e]
[fv-az1280-696:13960] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8fc0a288ff]
[fv-az1280-696:13960] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8fc0ea5ff5]
[fv-az1280-696:13960] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8fc0ebb0da]
[fv-az1280-696:13960] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8fc0ea5a55]
[fv-az1280-696:13960] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8fc0ea5a6f]
[fv-az1280-696:13960] [ 8] plumed(+0x146dd)[0x560d35e096dd]
[fv-az1280-696:13960] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8fc0a2a1ca]
[fv-az1280-696:13960] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8fc0a2a28b]
[fv-az1280-696:13960] [11] plumed(+0x15365)[0x560d35e0a365]
[fv-az1280-696:13960] *** End of error message ***
</pre>
{% endraw %}
