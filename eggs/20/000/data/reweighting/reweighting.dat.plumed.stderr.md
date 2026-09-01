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
[runnervmgx7h7:12110] *** Process received signal ***
[runnervmgx7h7:12110] Signal: Aborted (6)
[runnervmgx7h7:12110] Signal code:  (-6)
[runnervmgx7h7:12110] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8f39c45330]
[runnervmgx7h7:12110] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8f39c9ec0c]
[runnervmgx7h7:12110] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8f39c4527e]
[runnervmgx7h7:12110] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8f39c288ff]
[runnervmgx7h7:12110] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8f3a0a5ff5]
[runnervmgx7h7:12110] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8f3a0bb0da]
[runnervmgx7h7:12110] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8f3a0a5a55]
[runnervmgx7h7:12110] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8f3a0a5a6f]
[runnervmgx7h7:12110] [ 8] plumed(+0x146dd)[0x56490b91c6dd]
[runnervmgx7h7:12110] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8f39c2a1ca]
[runnervmgx7h7:12110] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8f39c2a28b]
[runnervmgx7h7:12110] [11] plumed(+0x15365)[0x56490b91d365]
[runnervmgx7h7:12110] *** End of error message ***
</pre>
{% endraw %}
