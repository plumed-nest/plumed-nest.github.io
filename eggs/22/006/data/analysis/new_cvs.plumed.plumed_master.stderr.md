**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/new_cvs.plumed   
Download: [zipped raw stdout](new_cvs.plumed.plumed_master.stdout.txt.zip) - [zipped raw stderr](new_cvs.plumed.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s43 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmgx7h7:06928] *** Process received signal ***
[runnervmgx7h7:06928] Signal: Aborted (6)
[runnervmgx7h7:06928] Signal code:  (-6)
[runnervmgx7h7:06928] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3961c45330]
[runnervmgx7h7:06928] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3961c9ec0c]
[runnervmgx7h7:06928] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3961c4527e]
[runnervmgx7h7:06928] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3961c288ff]
[runnervmgx7h7:06928] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f39620a5ff5]
[runnervmgx7h7:06928] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f39620bb0da]
[runnervmgx7h7:06928] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f39620a5a55]
[runnervmgx7h7:06928] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f39620a5a6f]
[runnervmgx7h7:06928] [ 8] plumed_master(+0x146dd)[0x5565e9fe26dd]
[runnervmgx7h7:06928] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3961c2a1ca]
[runnervmgx7h7:06928] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3961c2a28b]
[runnervmgx7h7:06928] [11] plumed_master(+0x15365)[0x5565e9fe3365]
[runnervmgx7h7:06928] *** End of error message ***
</pre>
{% endraw %}
