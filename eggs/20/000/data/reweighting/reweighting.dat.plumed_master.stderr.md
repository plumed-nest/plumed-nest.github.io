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
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @20 : keyword ARG is compulsory for this action
[runnervmw9dnm:10697] *** Process received signal ***
[runnervmw9dnm:10697] Signal: Aborted (6)
[runnervmw9dnm:10697] Signal code:  (-6)
[runnervmw9dnm:10697] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7f0ca45330]
[runnervmw9dnm:10697] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7f0ca9eb2c]
[runnervmw9dnm:10697] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7f0ca4527e]
[runnervmw9dnm:10697] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7f0ca288ff]
[runnervmw9dnm:10697] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7f0cea5ff5]
[runnervmw9dnm:10697] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7f0cebb0da]
[runnervmw9dnm:10697] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7f0cea5a55]
[runnervmw9dnm:10697] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7f0cea5a6f]
[runnervmw9dnm:10697] [ 8] plumed_master(+0x146dd)[0x5566c0ac76dd]
[runnervmw9dnm:10697] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7f0ca2a1ca]
[runnervmw9dnm:10697] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7f0ca2a28b]
[runnervmw9dnm:10697] [11] plumed_master(+0x15365)[0x5566c0ac8365]
[runnervmw9dnm:10697] *** End of error message ***
</pre>
{% endraw %}
