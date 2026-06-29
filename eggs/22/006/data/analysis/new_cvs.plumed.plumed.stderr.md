**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/new_cvs.plumed   
Download: [zipped raw stdout](new_cvs.plumed.plumed.stdout.txt.zip) - [zipped raw stderr](new_cvs.plumed.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s46 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmmklqx:07795] *** Process received signal ***
[runnervmmklqx:07795] Signal: Aborted (6)
[runnervmmklqx:07795] Signal code:  (-6)
[runnervmmklqx:07795] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa1ed445330]
[runnervmmklqx:07795] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa1ed49eb2c]
[runnervmmklqx:07795] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa1ed44527e]
[runnervmmklqx:07795] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa1ed4288ff]
[runnervmmklqx:07795] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa1ed8a5ff5]
[runnervmmklqx:07795] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa1ed8bb0da]
[runnervmmklqx:07795] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa1ed8a5a55]
[runnervmmklqx:07795] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa1ed8a5a6f]
[runnervmmklqx:07795] [ 8] plumed(+0x146dd)[0x56272501c6dd]
[runnervmmklqx:07795] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa1ed42a1ca]
[runnervmmklqx:07795] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa1ed42a28b]
[runnervmmklqx:07795] [11] plumed(+0x15365)[0x56272501d365]
[runnervmmklqx:07795] *** End of error message ***
</pre>
{% endraw %}
