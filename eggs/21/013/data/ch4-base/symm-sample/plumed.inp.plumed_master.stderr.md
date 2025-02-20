**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/symm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @47 : keyword ARG is compulsory for this action
[fv-az1691-811:10382] *** Process received signal ***
[fv-az1691-811:10382] Signal: Aborted (6)
[fv-az1691-811:10382] Signal code:  (-6)
[fv-az1691-811:10382] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe2a0245330]
[fv-az1691-811:10382] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe2a029eb2c]
[fv-az1691-811:10382] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe2a024527e]
[fv-az1691-811:10382] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe2a02288ff]
[fv-az1691-811:10382] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe2a06a5ff5]
[fv-az1691-811:10382] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe2a06bb0da]
[fv-az1691-811:10382] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe2a06a5a55]
[fv-az1691-811:10382] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe2a06a5a6f]
[fv-az1691-811:10382] [ 8] plumed_master(+0x146dd)[0x55b28a56b6dd]
[fv-az1691-811:10382] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe2a022a1ca]
[fv-az1691-811:10382] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe2a022a28b]
[fv-az1691-811:10382] [11] plumed_master(+0x15365)[0x55b28a56c365]
[fv-az1691-811:10382] *** End of error message ***
</pre>
{% endraw %}
