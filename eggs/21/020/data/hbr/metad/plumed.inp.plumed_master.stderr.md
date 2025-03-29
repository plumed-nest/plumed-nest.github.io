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
[fv-az1947-163:64715] *** Process received signal ***
[fv-az1947-163:64715] Signal: Aborted (6)
[fv-az1947-163:64715] Signal code:  (-6)
[fv-az1947-163:64715] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa2ba045330]
[fv-az1947-163:64715] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa2ba09eb2c]
[fv-az1947-163:64715] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa2ba04527e]
[fv-az1947-163:64715] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa2ba0288ff]
[fv-az1947-163:64715] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa2ba4a5ff5]
[fv-az1947-163:64715] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa2ba4bb0da]
[fv-az1947-163:64715] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa2ba4a5a55]
[fv-az1947-163:64715] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa2ba4a5a6f]
[fv-az1947-163:64715] [ 8] plumed_master(+0x146dd)[0x555cf02746dd]
[fv-az1947-163:64715] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa2ba02a1ca]
[fv-az1947-163:64715] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa2ba02a28b]
[fv-az1947-163:64715] [11] plumed_master(+0x15365)[0x555cf0275365]
[fv-az1947-163:64715] *** End of error message ***
</pre>
{% endraw %}
