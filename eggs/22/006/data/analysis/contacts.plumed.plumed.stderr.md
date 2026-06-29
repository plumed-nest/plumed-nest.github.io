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
[runnervmmklqx:07718] *** Process received signal ***
[runnervmmklqx:07718] Signal: Aborted (6)
[runnervmmklqx:07718] Signal code:  (-6)
[runnervmmklqx:07718] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fead3845330]
[runnervmmklqx:07718] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fead389eb2c]
[runnervmmklqx:07718] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fead384527e]
[runnervmmklqx:07718] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fead38288ff]
[runnervmmklqx:07718] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fead3ca5ff5]
[runnervmmklqx:07718] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fead3cbb0da]
[runnervmmklqx:07718] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fead3ca5a55]
[runnervmmklqx:07718] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fead3ca5a6f]
[runnervmmklqx:07718] [ 8] plumed(+0x146dd)[0x55e4ef8f26dd]
[runnervmmklqx:07718] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fead382a1ca]
[runnervmmklqx:07718] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fead382a28b]
[runnervmmklqx:07718] [11] plumed(+0x15365)[0x55e4ef8f3365]
[runnervmmklqx:07718] *** End of error message ***
</pre>
{% endraw %}
