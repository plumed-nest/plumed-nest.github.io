**Project ID:** [plumID:19.050]({{ '/' | absolute_url }}eggs/19/050/)  
Stderr for source:  plumed_histogram.dat   
Download: [zipped raw stdout](plumed_histogram.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_histogram.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s12 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmgx7h7:12454] *** Process received signal ***
[runnervmgx7h7:12454] Signal: Aborted (6)
[runnervmgx7h7:12454] Signal code:  (-6)
[runnervmgx7h7:12454] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff523645330]
[runnervmgx7h7:12454] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff52369ec0c]
[runnervmgx7h7:12454] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff52364527e]
[runnervmgx7h7:12454] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff5236288ff]
[runnervmgx7h7:12454] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff523aa5ff5]
[runnervmgx7h7:12454] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff523abb0da]
[runnervmgx7h7:12454] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff523aa5a55]
[runnervmgx7h7:12454] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff523aa5a6f]
[runnervmgx7h7:12454] [ 8] plumed_master(+0x146dd)[0x55ec6f60d6dd]
[runnervmgx7h7:12454] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff52362a1ca]
[runnervmgx7h7:12454] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff52362a28b]
[runnervmgx7h7:12454] [11] plumed_master(+0x15365)[0x55ec6f60e365]
[runnervmgx7h7:12454] *** End of error message ***
</pre>
{% endraw %}
