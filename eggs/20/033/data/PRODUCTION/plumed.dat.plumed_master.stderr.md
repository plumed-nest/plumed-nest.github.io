**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action WHOLEMOLECULES with label @5 : cannot understand the following words from the input line : REF0, REF1, REF2
[runnervmw9dnm:09974] *** Process received signal ***
[runnervmw9dnm:09974] Signal: Aborted (6)
[runnervmw9dnm:09974] Signal code:  (-6)
[runnervmw9dnm:09974] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1cece45330]
[runnervmw9dnm:09974] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1cece9eb2c]
[runnervmw9dnm:09974] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1cece4527e]
[runnervmw9dnm:09974] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1cece288ff]
[runnervmw9dnm:09974] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1ced2a5ff5]
[runnervmw9dnm:09974] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1ced2bb0da]
[runnervmw9dnm:09974] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1ced2a5a55]
[runnervmw9dnm:09974] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1ced2a5a6f]
[runnervmw9dnm:09974] [ 8] plumed_master(+0x146dd)[0x5585177d16dd]
[runnervmw9dnm:09974] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1cece2a1ca]
[runnervmw9dnm:09974] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1cece2a28b]
[runnervmw9dnm:09974] [11] plumed_master(+0x15365)[0x5585177d2365]
[runnervmw9dnm:09974] *** End of error message ***
</pre>
{% endraw %}
