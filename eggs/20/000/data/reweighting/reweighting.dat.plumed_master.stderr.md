**Project ID:** [plumID:20.000]({{ '/' | absolute_url }}eggs/20/000/)  
Stderr for source:  reweighting/reweighting.dat   
Download: [zipped raw stdout](reweighting.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweighting.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @17 : keyword ARG is compulsory for this action
[fv-az2209-645:67674] *** Process received signal ***
[fv-az2209-645:67674] Signal: Aborted (6)
[fv-az2209-645:67674] Signal code:  (-6)
[fv-az2209-645:67674] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5c53045330]
[fv-az2209-645:67674] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5c5309eb2c]
[fv-az2209-645:67674] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5c5304527e]
[fv-az2209-645:67674] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5c530288ff]
[fv-az2209-645:67674] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5c534a5ff5]
[fv-az2209-645:67674] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5c534bb0da]
[fv-az2209-645:67674] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5c534a5a55]
[fv-az2209-645:67674] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5c534a5a6f]
[fv-az2209-645:67674] [ 8] plumed_master(+0x146dd)[0x562da9d566dd]
[fv-az2209-645:67674] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5c5302a1ca]
[fv-az2209-645:67674] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5c5302a28b]
[fv-az2209-645:67674] [11] plumed_master(+0x15365)[0x562da9d57365]
[fv-az2209-645:67674] *** End of error message ***
</pre>
{% endraw %}
