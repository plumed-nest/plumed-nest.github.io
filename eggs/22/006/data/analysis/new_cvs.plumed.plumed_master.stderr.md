**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/new_cvs.plumed   
Download: [zipped raw stdout](new_cvs.plumed.plumed_master.stdout.txt.zip) - [zipped raw stderr](new_cvs.plumed.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @70 : keyword ARG is compulsory for this action
[runnervmw9dnm:09290] *** Process received signal ***
[runnervmw9dnm:09290] Signal: Aborted (6)
[runnervmw9dnm:09290] Signal code:  (-6)
[runnervmw9dnm:09290] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1746645330]
[runnervmw9dnm:09290] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f174669eb2c]
[runnervmw9dnm:09290] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f174664527e]
[runnervmw9dnm:09290] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f17466288ff]
[runnervmw9dnm:09290] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1746aa5ff5]
[runnervmw9dnm:09290] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1746abb0da]
[runnervmw9dnm:09290] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1746aa5a55]
[runnervmw9dnm:09290] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1746aa5a6f]
[runnervmw9dnm:09290] [ 8] plumed_master(+0x146dd)[0x55dbcaeeb6dd]
[runnervmw9dnm:09290] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f174662a1ca]
[runnervmw9dnm:09290] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f174662a28b]
[runnervmw9dnm:09290] [11] plumed_master(+0x15365)[0x55dbcaeec365]
[runnervmw9dnm:09290] *** End of error message ***
</pre>
{% endraw %}
