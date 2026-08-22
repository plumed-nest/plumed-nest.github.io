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
[runnervm76f27:07871] *** Process received signal ***
[runnervm76f27:07871] Signal: Aborted (6)
[runnervm76f27:07871] Signal code:  (-6)
[runnervm76f27:07871] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f45e0445330]
[runnervm76f27:07871] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f45e049ec0c]
[runnervm76f27:07871] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f45e044527e]
[runnervm76f27:07871] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f45e04288ff]
[runnervm76f27:07871] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f45e08a5ff5]
[runnervm76f27:07871] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f45e08bb0da]
[runnervm76f27:07871] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f45e08a5a55]
[runnervm76f27:07871] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f45e08a5a6f]
[runnervm76f27:07871] [ 8] plumed_master(+0x146dd)[0x55a8ca5106dd]
[runnervm76f27:07871] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f45e042a1ca]
[runnervm76f27:07871] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f45e042a28b]
[runnervm76f27:07871] [11] plumed_master(+0x15365)[0x55a8ca511365]
[runnervm76f27:07871] *** End of error message ***
</pre>
{% endraw %}
