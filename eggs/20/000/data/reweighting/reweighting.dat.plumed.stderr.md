**Project ID:** [plumID:20.000]({{ '/' | absolute_url }}eggs/20/000/)  
Stderr for source:  reweighting/reweighting.dat   
Download: [zipped raw stdout](reweighting.dat.plumed.stdout.txt.zip) - [zipped raw stderr](reweighting.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s13 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmmklqx:10123] *** Process received signal ***
[runnervmmklqx:10123] Signal: Aborted (6)
[runnervmmklqx:10123] Signal code:  (-6)
[runnervmmklqx:10123] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8fa7045330]
[runnervmmklqx:10123] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8fa709eb2c]
[runnervmmklqx:10123] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8fa704527e]
[runnervmmklqx:10123] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8fa70288ff]
[runnervmmklqx:10123] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8fa74a5ff5]
[runnervmmklqx:10123] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8fa74bb0da]
[runnervmmklqx:10123] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8fa74a5a55]
[runnervmmklqx:10123] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8fa74a5a6f]
[runnervmmklqx:10123] [ 8] plumed(+0x146dd)[0x562db57916dd]
[runnervmmklqx:10123] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8fa702a1ca]
[runnervmmklqx:10123] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8fa702a28b]
[runnervmmklqx:10123] [11] plumed(+0x15365)[0x562db5792365]
[runnervmmklqx:10123] *** End of error message ***
</pre>
{% endraw %}
