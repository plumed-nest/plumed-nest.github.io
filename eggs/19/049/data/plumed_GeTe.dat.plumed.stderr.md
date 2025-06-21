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
[pkrvmxyh4eaekms:14017] *** Process received signal ***
[pkrvmxyh4eaekms:14017] Signal: Aborted (6)
[pkrvmxyh4eaekms:14017] Signal code:  (-6)
[pkrvmxyh4eaekms:14017] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbe6fe45330]
[pkrvmxyh4eaekms:14017] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbe6fe9eb2c]
[pkrvmxyh4eaekms:14017] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbe6fe4527e]
[pkrvmxyh4eaekms:14017] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbe6fe288ff]
[pkrvmxyh4eaekms:14017] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbe702a5ff5]
[pkrvmxyh4eaekms:14017] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbe702bb0da]
[pkrvmxyh4eaekms:14017] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbe702a5a55]
[pkrvmxyh4eaekms:14017] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbe702a5a6f]
[pkrvmxyh4eaekms:14017] [ 8] plumed(+0x146dd)[0x560f2337c6dd]
[pkrvmxyh4eaekms:14017] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbe6fe2a1ca]
[pkrvmxyh4eaekms:14017] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbe6fe2a28b]
[pkrvmxyh4eaekms:14017] [11] plumed(+0x15365)[0x560f2337d365]
[pkrvmxyh4eaekms:14017] *** End of error message ***
</pre>
{% endraw %}
