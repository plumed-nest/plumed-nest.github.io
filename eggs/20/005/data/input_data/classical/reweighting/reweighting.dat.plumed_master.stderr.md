**Project ID:** [plumID:20.005]({{ '/' | absolute_url }}eggs/20/005/)  
Stderr for source:  input_data/classical/reweighting/reweighting.dat   
Download: [zipped raw stdout](reweighting.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweighting.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s12 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmmklqx:10716] *** Process received signal ***
[runnervmmklqx:10716] Signal: Aborted (6)
[runnervmmklqx:10716] Signal code:  (-6)
[runnervmmklqx:10716] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd322e45330]
[runnervmmklqx:10716] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd322e9eb2c]
[runnervmmklqx:10716] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd322e4527e]
[runnervmmklqx:10716] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd322e288ff]
[runnervmmklqx:10716] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd3232a5ff5]
[runnervmmklqx:10716] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd3232bb0da]
[runnervmmklqx:10716] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd3232a5a55]
[runnervmmklqx:10716] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd3232a5a6f]
[runnervmmklqx:10716] [ 8] plumed_master(+0x146dd)[0x55b92a97d6dd]
[runnervmmklqx:10716] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd322e2a1ca]
[runnervmmklqx:10716] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd322e2a28b]
[runnervmmklqx:10716] [11] plumed_master(+0x15365)[0x55b92a97e365]
[runnervmmklqx:10716] *** End of error message ***
</pre>
{% endraw %}
