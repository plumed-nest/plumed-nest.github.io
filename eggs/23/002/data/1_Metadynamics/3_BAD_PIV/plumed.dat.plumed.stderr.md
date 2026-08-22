**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/3_BAD_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervm76f27:07571] *** Process received signal ***
[runnervm76f27:07571] Signal: Aborted (6)
[runnervm76f27:07571] Signal code:  (-6)
[runnervm76f27:07571] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7a99445330]
[runnervm76f27:07571] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7a9949ec0c]
[runnervm76f27:07571] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7a9944527e]
[runnervm76f27:07571] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7a994288ff]
[runnervm76f27:07571] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7a998a5ff5]
[runnervm76f27:07571] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7a998bb0da]
[runnervm76f27:07571] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7a998a5a55]
[runnervm76f27:07571] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7a998a5a6f]
[runnervm76f27:07571] [ 8] plumed(+0x146dd)[0x556cf7b146dd]
[runnervm76f27:07571] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7a9942a1ca]
[runnervm76f27:07571] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7a9942a28b]
[runnervm76f27:07571] [11] plumed(+0x15365)[0x556cf7b15365]
[runnervm76f27:07571] *** End of error message ***
</pre>
{% endraw %}
