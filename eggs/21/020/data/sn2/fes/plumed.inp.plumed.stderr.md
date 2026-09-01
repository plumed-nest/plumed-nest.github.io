**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  sn2/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s23 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmgx7h7:08511] *** Process received signal ***
[runnervmgx7h7:08511] Signal: Aborted (6)
[runnervmgx7h7:08511] Signal code:  (-6)
[runnervmgx7h7:08511] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3c8e645330]
[runnervmgx7h7:08511] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3c8e69ec0c]
[runnervmgx7h7:08511] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3c8e64527e]
[runnervmgx7h7:08511] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3c8e6288ff]
[runnervmgx7h7:08511] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3c8eaa5ff5]
[runnervmgx7h7:08511] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3c8eabb0da]
[runnervmgx7h7:08511] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3c8eaa5a55]
[runnervmgx7h7:08511] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3c8eaa5a6f]
[runnervmgx7h7:08511] [ 8] plumed(+0x146dd)[0x5558329066dd]
[runnervmgx7h7:08511] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3c8e62a1ca]
[runnervmgx7h7:08511] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3c8e62a28b]
[runnervmgx7h7:08511] [11] plumed(+0x15365)[0x555832907365]
[runnervmgx7h7:08511] *** End of error message ***
</pre>
{% endraw %}
