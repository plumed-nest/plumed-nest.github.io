**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/2_Entropy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervm76f27:07518] *** Process received signal ***
[runnervm76f27:07518] Signal: Aborted (6)
[runnervm76f27:07518] Signal code:  (-6)
[runnervm76f27:07518] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fca00a45330]
[runnervm76f27:07518] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fca00a9ec0c]
[runnervm76f27:07518] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fca00a4527e]
[runnervm76f27:07518] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fca00a288ff]
[runnervm76f27:07518] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fca00ea5ff5]
[runnervm76f27:07518] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fca00ebb0da]
[runnervm76f27:07518] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fca00ea5a55]
[runnervm76f27:07518] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fca00ea5a6f]
[runnervm76f27:07518] [ 8] plumed(+0x146dd)[0x55e0a6a2d6dd]
[runnervm76f27:07518] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fca00a2a1ca]
[runnervm76f27:07518] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fca00a2a28b]
[runnervm76f27:07518] [11] plumed(+0x15365)[0x55e0a6a2e365]
[runnervm76f27:07518] *** End of error message ***
</pre>
{% endraw %}
