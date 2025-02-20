**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/metad/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @52 : keyword ARG is compulsory for this action
[fv-az816-356:11847] *** Process received signal ***
[fv-az816-356:11847] Signal: Aborted (6)
[fv-az816-356:11847] Signal code:  (-6)
[fv-az816-356:11847] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f469d445330]
[fv-az816-356:11847] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f469d49eb2c]
[fv-az816-356:11847] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f469d44527e]
[fv-az816-356:11847] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f469d4288ff]
[fv-az816-356:11847] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f469d8a5ff5]
[fv-az816-356:11847] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f469d8bb0da]
[fv-az816-356:11847] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f469d8a5a55]
[fv-az816-356:11847] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f469d8a5a6f]
[fv-az816-356:11847] [ 8] plumed_master(+0x146dd)[0x560a238a66dd]
[fv-az816-356:11847] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f469d42a1ca]
[fv-az816-356:11847] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f469d42a28b]
[fv-az816-356:11847] [11] plumed_master(+0x15365)[0x560a238a7365]
[fv-az816-356:11847] *** End of error message ***
</pre>
{% endraw %}
