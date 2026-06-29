**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  dimer/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s19 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmmklqx:09176] *** Process received signal ***
[runnervmmklqx:09176] Signal: Aborted (6)
[runnervmmklqx:09176] Signal code:  (-6)
[runnervmmklqx:09176] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8ae8245330]
[runnervmmklqx:09176] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8ae829eb2c]
[runnervmmklqx:09176] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8ae824527e]
[runnervmmklqx:09176] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8ae82288ff]
[runnervmmklqx:09176] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8ae86a5ff5]
[runnervmmklqx:09176] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8ae86bb0da]
[runnervmmklqx:09176] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8ae86a5a55]
[runnervmmklqx:09176] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8ae86a5a6f]
[runnervmmklqx:09176] [ 8] plumed(+0x146dd)[0x55a0f8baf6dd]
[runnervmmklqx:09176] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8ae822a1ca]
[runnervmmklqx:09176] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8ae822a28b]
[runnervmmklqx:09176] [11] plumed(+0x15365)[0x55a0f8bb0365]
[runnervmmklqx:09176] *** End of error message ***
</pre>
{% endraw %}
