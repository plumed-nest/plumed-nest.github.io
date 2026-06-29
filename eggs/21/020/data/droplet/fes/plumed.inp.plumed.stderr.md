**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  droplet/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s32 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmmklqx:09025] *** Process received signal ***
[runnervmmklqx:09025] Signal: Aborted (6)
[runnervmmklqx:09025] Signal code:  (-6)
[runnervmmklqx:09025] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f99f6c45330]
[runnervmmklqx:09025] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f99f6c9eb2c]
[runnervmmklqx:09025] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f99f6c4527e]
[runnervmmklqx:09025] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f99f6c288ff]
[runnervmmklqx:09025] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f99f70a5ff5]
[runnervmmklqx:09025] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f99f70bb0da]
[runnervmmklqx:09025] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f99f70a5a55]
[runnervmmklqx:09025] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f99f70a5a6f]
[runnervmmklqx:09025] [ 8] plumed(+0x146dd)[0x55db03b036dd]
[runnervmmklqx:09025] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f99f6c2a1ca]
[runnervmmklqx:09025] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f99f6c2a28b]
[runnervmmklqx:09025] [11] plumed(+0x15365)[0x55db03b04365]
[runnervmmklqx:09025] *** End of error message ***
</pre>
{% endraw %}
