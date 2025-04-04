**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  sn2/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @44 : keyword ARG is compulsory for this action
[fv-az2207-973:09840] *** Process received signal ***
[fv-az2207-973:09840] Signal: Aborted (6)
[fv-az2207-973:09840] Signal code:  (-6)
[fv-az2207-973:09840] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3939045330]
[fv-az2207-973:09840] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f393909eb2c]
[fv-az2207-973:09840] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f393904527e]
[fv-az2207-973:09840] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f39390288ff]
[fv-az2207-973:09840] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f39394a5ff5]
[fv-az2207-973:09840] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f39394bb0da]
[fv-az2207-973:09840] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f39394a5a55]
[fv-az2207-973:09840] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f39394a5a6f]
[fv-az2207-973:09840] [ 8] plumed_master(+0x146dd)[0x5568052b26dd]
[fv-az2207-973:09840] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f393902a1ca]
[fv-az2207-973:09840] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f393902a28b]
[fv-az2207-973:09840] [11] plumed_master(+0x15365)[0x5568052b3365]
[fv-az2207-973:09840] *** End of error message ***
</pre>
{% endraw %}
