**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/contacts.plumed   
Download: [zipped raw stdout](contacts.plumed.plumed_master.stdout.txt.zip) - [zipped raw stderr](contacts.plumed.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s39 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmgx7h7:06851] *** Process received signal ***
[runnervmgx7h7:06851] Signal: Aborted (6)
[runnervmgx7h7:06851] Signal code:  (-6)
[runnervmgx7h7:06851] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9571a45330]
[runnervmgx7h7:06851] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9571a9ec0c]
[runnervmgx7h7:06851] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9571a4527e]
[runnervmgx7h7:06851] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9571a288ff]
[runnervmgx7h7:06851] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9571ea5ff5]
[runnervmgx7h7:06851] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9571ebb0da]
[runnervmgx7h7:06851] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9571ea5a55]
[runnervmgx7h7:06851] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9571ea5a6f]
[runnervmgx7h7:06851] [ 8] plumed_master(+0x146dd)[0x55a26b7fd6dd]
[runnervmgx7h7:06851] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9571a2a1ca]
[runnervmgx7h7:06851] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9571a2a28b]
[runnervmgx7h7:06851] [11] plumed_master(+0x15365)[0x55a26b7fe365]
[runnervmgx7h7:06851] *** End of error message ***
</pre>
{% endraw %}
