**Project ID:** [plumID:19.050]({{ '/' | absolute_url }}eggs/19/050/)  
Stderr for source:  plumed_histogram.dat   
Download: [zipped raw stdout](plumed_histogram.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_histogram.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @33 : keyword ARG is compulsory for this action
[fv-az1370-99:66915] *** Process received signal ***
[fv-az1370-99:66915] Signal: Aborted (6)
[fv-az1370-99:66915] Signal code:  (-6)
[fv-az1370-99:66915] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f23c4045330]
[fv-az1370-99:66915] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f23c409eb2c]
[fv-az1370-99:66915] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f23c404527e]
[fv-az1370-99:66915] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f23c40288ff]
[fv-az1370-99:66915] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f23c44a5ff5]
[fv-az1370-99:66915] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f23c44bb0da]
[fv-az1370-99:66915] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f23c44a5a55]
[fv-az1370-99:66915] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f23c44a5a6f]
[fv-az1370-99:66915] [ 8] plumed_master(+0x146dd)[0x55c5d12006dd]
[fv-az1370-99:66915] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f23c402a1ca]
[fv-az1370-99:66915] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f23c402a28b]
[fv-az1370-99:66915] [11] plumed_master(+0x15365)[0x55c5d1201365]
[fv-az1370-99:66915] *** End of error message ***
</pre>
{% endraw %}
