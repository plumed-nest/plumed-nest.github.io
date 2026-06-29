**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/new_cvs.plumed   
Download: [zipped raw stdout](new_cvs.plumed.plumed_master.stdout.txt.zip) - [zipped raw stderr](new_cvs.plumed.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s43 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmmklqx:07812] *** Process received signal ***
[runnervmmklqx:07812] Signal: Aborted (6)
[runnervmmklqx:07812] Signal code:  (-6)
[runnervmmklqx:07812] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0787c45330]
[runnervmmklqx:07812] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0787c9eb2c]
[runnervmmklqx:07812] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0787c4527e]
[runnervmmklqx:07812] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0787c288ff]
[runnervmmklqx:07812] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f07880a5ff5]
[runnervmmklqx:07812] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f07880bb0da]
[runnervmmklqx:07812] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f07880a5a55]
[runnervmmklqx:07812] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f07880a5a6f]
[runnervmmklqx:07812] [ 8] plumed_master(+0x146dd)[0x5566254b26dd]
[runnervmmklqx:07812] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0787c2a1ca]
[runnervmmklqx:07812] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0787c2a28b]
[runnervmmklqx:07812] [11] plumed_master(+0x15365)[0x5566254b3365]
[runnervmmklqx:07812] *** End of error message ***
</pre>
{% endraw %}
