**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/contacts.plumed   
Download: [zipped raw stdout](contacts.plumed.plumed.stdout.txt.zip) - [zipped raw stderr](contacts.plumed.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s41 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmgx7h7:06835] *** Process received signal ***
[runnervmgx7h7:06835] Signal: Aborted (6)
[runnervmgx7h7:06835] Signal code:  (-6)
[runnervmgx7h7:06835] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f87e4245330]
[runnervmgx7h7:06835] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f87e429ec0c]
[runnervmgx7h7:06835] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f87e424527e]
[runnervmgx7h7:06835] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f87e42288ff]
[runnervmgx7h7:06835] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f87e46a5ff5]
[runnervmgx7h7:06835] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f87e46bb0da]
[runnervmgx7h7:06835] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f87e46a5a55]
[runnervmgx7h7:06835] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f87e46a5a6f]
[runnervmgx7h7:06835] [ 8] plumed(+0x146dd)[0x555953cef6dd]
[runnervmgx7h7:06835] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f87e422a1ca]
[runnervmgx7h7:06835] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f87e422a28b]
[runnervmgx7h7:06835] [11] plumed(+0x15365)[0x555953cf0365]
[runnervmgx7h7:06835] *** End of error message ***
</pre>
{% endraw %}
