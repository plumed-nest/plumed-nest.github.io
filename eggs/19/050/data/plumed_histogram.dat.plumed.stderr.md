**Project ID:** [plumID:19.050]({{ '/' | absolute_url }}eggs/19/050/)  
Stderr for source:  plumed_histogram.dat   
Download: [zipped raw stdout](plumed_histogram.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_histogram.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s12 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmvrwv9:11896] *** Process received signal ***
[runnervmvrwv9:11896] Signal: Aborted (6)
[runnervmvrwv9:11896] Signal code:  (-6)
[runnervmvrwv9:11896] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8ba9445330]
[runnervmvrwv9:11896] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8ba949eb2c]
[runnervmvrwv9:11896] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8ba944527e]
[runnervmvrwv9:11896] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8ba94288ff]
[runnervmvrwv9:11896] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8ba98a5ff5]
[runnervmvrwv9:11896] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8ba98bb0da]
[runnervmvrwv9:11896] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8ba98a5a55]
[runnervmvrwv9:11896] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8ba98a5a6f]
[runnervmvrwv9:11896] [ 8] plumed(+0x146dd)[0x55bf035e86dd]
[runnervmvrwv9:11896] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8ba942a1ca]
[runnervmvrwv9:11896] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8ba942a28b]
[runnervmvrwv9:11896] [11] plumed(+0x15365)[0x55bf035e9365]
[runnervmvrwv9:11896] *** End of error message ***
</pre>
{% endraw %}
