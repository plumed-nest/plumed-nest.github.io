**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/new_cvs.plumed   
Download: [zipped raw stdout](new_cvs.plumed.plumed_master.stdout.txt.zip) - [zipped raw stderr](new_cvs.plumed.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @70 : keyword ARG is compulsory for this action
[runnervmkj6or:06480] *** Process received signal ***
[runnervmkj6or:06480] Signal: Aborted (6)
[runnervmkj6or:06480] Signal code:  (-6)
[runnervmkj6or:06480] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9c59245330]
[runnervmkj6or:06480] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9c5929eb2c]
[runnervmkj6or:06480] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9c5924527e]
[runnervmkj6or:06480] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9c592288ff]
[runnervmkj6or:06480] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9c596a5ff5]
[runnervmkj6or:06480] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9c596bb0da]
[runnervmkj6or:06480] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9c596a5a55]
[runnervmkj6or:06480] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9c596a5a6f]
[runnervmkj6or:06480] [ 8] plumed_master(+0x146dd)[0x55ec237cc6dd]
[runnervmkj6or:06480] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9c5922a1ca]
[runnervmkj6or:06480] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9c5922a28b]
[runnervmkj6or:06480] [11] plumed_master(+0x15365)[0x55ec237cd365]
[runnervmkj6or:06480] *** End of error message ***
</pre>
{% endraw %}
