**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[runnervm76f27:06968] *** Process received signal ***
[runnervm76f27:06968] Signal: Aborted (6)
[runnervm76f27:06968] Signal code:  (-6)
[runnervm76f27:06968] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5046245330]
[runnervm76f27:06968] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f504629ec0c]
[runnervm76f27:06968] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f504624527e]
[runnervm76f27:06968] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f50462288ff]
[runnervm76f27:06968] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f50466a5ff5]
[runnervm76f27:06968] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f50466bb0da]
[runnervm76f27:06968] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f50466a5a55]
[runnervm76f27:06968] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f50466a5a6f]
[runnervm76f27:06968] [ 8] plumed(+0x146dd)[0x5580e81786dd]
[runnervm76f27:06968] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f504622a1ca]
[runnervm76f27:06968] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f504622a28b]
[runnervm76f27:06968] [11] plumed(+0x15365)[0x5580e8179365]
[runnervm76f27:06968] *** End of error message ***
</pre>
{% endraw %}
