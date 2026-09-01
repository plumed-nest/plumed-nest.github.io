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
[runnervmgx7h7:06912] *** Process received signal ***
[runnervmgx7h7:06912] Signal: Aborted (6)
[runnervmgx7h7:06912] Signal code:  (-6)
[runnervmgx7h7:06912] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5c57845330]
[runnervmgx7h7:06912] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5c5789ec0c]
[runnervmgx7h7:06912] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5c5784527e]
[runnervmgx7h7:06912] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5c578288ff]
[runnervmgx7h7:06912] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5c57ca5ff5]
[runnervmgx7h7:06912] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5c57cbb0da]
[runnervmgx7h7:06912] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5c57ca5a55]
[runnervmgx7h7:06912] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5c57ca5a6f]
[runnervmgx7h7:06912] [ 8] plumed(+0x146dd)[0x55b5fc1db6dd]
[runnervmgx7h7:06912] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5c5782a1ca]
[runnervmgx7h7:06912] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5c5782a28b]
[runnervmgx7h7:06912] [11] plumed(+0x15365)[0x55b5fc1dc365]
[runnervmgx7h7:06912] *** End of error message ***
</pre>
{% endraw %}
