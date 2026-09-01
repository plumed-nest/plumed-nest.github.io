**Project ID:** [plumID:20.026]({{ '/' | absolute_url }}eggs/20/026/)  
Stderr for source:  plumed_WTMD.dat   
Download: [zipped raw stdout](plumed_WTMD.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_WTMD.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s58 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmgx7h7:10207] *** Process received signal ***
[runnervmgx7h7:10207] Signal: Aborted (6)
[runnervmgx7h7:10207] Signal code:  (-6)
[runnervmgx7h7:10207] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc122645330]
[runnervmgx7h7:10207] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc12269ec0c]
[runnervmgx7h7:10207] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc12264527e]
[runnervmgx7h7:10207] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc1226288ff]
[runnervmgx7h7:10207] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc122aa5ff5]
[runnervmgx7h7:10207] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc122abb0da]
[runnervmgx7h7:10207] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc122aa5a55]
[runnervmgx7h7:10207] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc122aa5a6f]
[runnervmgx7h7:10207] [ 8] plumed(+0x146dd)[0x5612419fa6dd]
[runnervmgx7h7:10207] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc12262a1ca]
[runnervmgx7h7:10207] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc12262a28b]
[runnervmgx7h7:10207] [11] plumed(+0x15365)[0x5612419fb365]
[runnervmgx7h7:10207] *** End of error message ***
</pre>
{% endraw %}
