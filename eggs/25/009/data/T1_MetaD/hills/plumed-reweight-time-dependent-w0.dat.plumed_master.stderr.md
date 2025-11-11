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
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @23 : keyword ARG is compulsory for this action
[runnervmw9dnm:06227] *** Process received signal ***
[runnervmw9dnm:06227] Signal: Aborted (6)
[runnervmw9dnm:06227] Signal code:  (-6)
[runnervmw9dnm:06227] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5b28445330]
[runnervmw9dnm:06227] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5b2849eb2c]
[runnervmw9dnm:06227] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5b2844527e]
[runnervmw9dnm:06227] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5b284288ff]
[runnervmw9dnm:06227] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5b288a5ff5]
[runnervmw9dnm:06227] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5b288bb0da]
[runnervmw9dnm:06227] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5b288a5a55]
[runnervmw9dnm:06227] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5b288a5a6f]
[runnervmw9dnm:06227] [ 8] plumed_master(+0x146dd)[0x561bd68d96dd]
[runnervmw9dnm:06227] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5b2842a1ca]
[runnervmw9dnm:06227] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5b2842a28b]
[runnervmw9dnm:06227] [11] plumed_master(+0x15365)[0x561bd68da365]
[runnervmw9dnm:06227] *** End of error message ***
</pre>
{% endraw %}
