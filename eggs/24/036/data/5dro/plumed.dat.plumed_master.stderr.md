**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  5dro/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @20 : keyword ARG is compulsory for this action
[runnervmw9dnm:06708] *** Process received signal ***
[runnervmw9dnm:06708] Signal: Aborted (6)
[runnervmw9dnm:06708] Signal code:  (-6)
[runnervmw9dnm:06708] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6802645330]
[runnervmw9dnm:06708] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f680269eb2c]
[runnervmw9dnm:06708] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f680264527e]
[runnervmw9dnm:06708] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f68026288ff]
[runnervmw9dnm:06708] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6802aa5ff5]
[runnervmw9dnm:06708] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6802abb0da]
[runnervmw9dnm:06708] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6802aa5a55]
[runnervmw9dnm:06708] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6802aa5a6f]
[runnervmw9dnm:06708] [ 8] plumed_master(+0x146dd)[0x5598a48826dd]
[runnervmw9dnm:06708] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f680262a1ca]
[runnervmw9dnm:06708] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f680262a28b]
[runnervmw9dnm:06708] [11] plumed_master(+0x15365)[0x5598a4883365]
[runnervmw9dnm:06708] *** End of error message ***
</pre>
{% endraw %}
