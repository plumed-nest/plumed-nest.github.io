**Project ID:** [plumID:25.009]({{ '/' | absolute_url }}eggs/25/009/)  
Stderr for source:  T1_MetaD/hills/plumed-reweight-time-dependent-w0.dat   
Download: [zipped raw stdout](plumed-reweight-time-dependent-w0.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-reweight-time-dependent-w0.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @33 : keyword ARG is compulsory for this action
[fv-az1050-229:60867] *** Process received signal ***
[fv-az1050-229:60867] Signal: Aborted (6)
[fv-az1050-229:60867] Signal code:  (-6)
[fv-az1050-229:60867] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7febf1245330]
[fv-az1050-229:60867] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7febf129eb2c]
[fv-az1050-229:60867] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7febf124527e]
[fv-az1050-229:60867] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7febf12288ff]
[fv-az1050-229:60867] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7febf16a5ff5]
[fv-az1050-229:60867] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7febf16bb0da]
[fv-az1050-229:60867] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7febf16a5a55]
[fv-az1050-229:60867] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7febf16a5a6f]
[fv-az1050-229:60867] [ 8] plumed_master(+0x146dd)[0x561d5394d6dd]
[fv-az1050-229:60867] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7febf122a1ca]
[fv-az1050-229:60867] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7febf122a28b]
[fv-az1050-229:60867] [11] plumed_master(+0x15365)[0x561d5394e365]
[fv-az1050-229:60867] *** End of error message ***
</pre>
{% endraw %}
