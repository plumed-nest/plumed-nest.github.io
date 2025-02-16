**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  sn2/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @44 : keyword ARG is compulsory for this action
[fv-az1440-40:64360] *** Process received signal ***
[fv-az1440-40:64360] Signal: Aborted (6)
[fv-az1440-40:64360] Signal code:  (-6)
[fv-az1440-40:64360] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc458245330]
[fv-az1440-40:64360] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc45829eb2c]
[fv-az1440-40:64360] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc45824527e]
[fv-az1440-40:64360] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc4582288ff]
[fv-az1440-40:64360] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc4586a5ff5]
[fv-az1440-40:64360] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc4586bb0da]
[fv-az1440-40:64360] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc4586a5a55]
[fv-az1440-40:64360] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc4586a5a6f]
[fv-az1440-40:64360] [ 8] plumed_master(+0x146dd)[0x55f5942536dd]
[fv-az1440-40:64360] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc45822a1ca]
[fv-az1440-40:64360] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc45822a28b]
[fv-az1440-40:64360] [11] plumed_master(+0x15365)[0x55f594254365]
[fv-az1440-40:64360] *** End of error message ***
</pre>
{% endraw %}
