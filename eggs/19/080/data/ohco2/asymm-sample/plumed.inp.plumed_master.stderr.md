**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  ohco2/asymm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @35 : keyword ARG is compulsory for this action
[fv-az2209-645:67744] *** Process received signal ***
[fv-az2209-645:67744] Signal: Aborted (6)
[fv-az2209-645:67744] Signal code:  (-6)
[fv-az2209-645:67744] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7462045330]
[fv-az2209-645:67744] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f746209eb2c]
[fv-az2209-645:67744] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f746204527e]
[fv-az2209-645:67744] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f74620288ff]
[fv-az2209-645:67744] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f74624a5ff5]
[fv-az2209-645:67744] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f74624bb0da]
[fv-az2209-645:67744] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f74624a5a55]
[fv-az2209-645:67744] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f74624a5a6f]
[fv-az2209-645:67744] [ 8] plumed_master(+0x146dd)[0x55ca46ff46dd]
[fv-az2209-645:67744] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f746202a1ca]
[fv-az2209-645:67744] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f746202a28b]
[fv-az2209-645:67744] [11] plumed_master(+0x15365)[0x55ca46ff5365]
[fv-az2209-645:67744] *** End of error message ***
</pre>
{% endraw %}
