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
[runnervm76f27:07855] *** Process received signal ***
[runnervm76f27:07855] Signal: Aborted (6)
[runnervm76f27:07855] Signal code:  (-6)
[runnervm76f27:07855] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f24e4845330]
[runnervm76f27:07855] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f24e489ec0c]
[runnervm76f27:07855] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f24e484527e]
[runnervm76f27:07855] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f24e48288ff]
[runnervm76f27:07855] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f24e4ca5ff5]
[runnervm76f27:07855] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f24e4cbb0da]
[runnervm76f27:07855] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f24e4ca5a55]
[runnervm76f27:07855] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f24e4ca5a6f]
[runnervm76f27:07855] [ 8] plumed(+0x146dd)[0x555f130bd6dd]
[runnervm76f27:07855] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f24e482a1ca]
[runnervm76f27:07855] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f24e482a28b]
[runnervm76f27:07855] [11] plumed(+0x15365)[0x555f130be365]
[runnervm76f27:07855] *** End of error message ***
</pre>
{% endraw %}
