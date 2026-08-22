**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_forward.dat   
Download: [zipped raw stdout](plumed_Argon_forward.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_forward.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[runnervm76f27:06879] *** Process received signal ***
[runnervm76f27:06879] Signal: Aborted (6)
[runnervm76f27:06879] Signal code:  (-6)
[runnervm76f27:06879] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd209045330]
[runnervm76f27:06879] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd20909ec0c]
[runnervm76f27:06879] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd20904527e]
[runnervm76f27:06879] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd2090288ff]
[runnervm76f27:06879] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd2094a5ff5]
[runnervm76f27:06879] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd2094bb0da]
[runnervm76f27:06879] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd2094a5a55]
[runnervm76f27:06879] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd2094a5a6f]
[runnervm76f27:06879] [ 8] plumed(+0x146dd)[0x562c0bd046dd]
[runnervm76f27:06879] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd20902a1ca]
[runnervm76f27:06879] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd20902a28b]
[runnervm76f27:06879] [11] plumed(+0x15365)[0x562c0bd05365]
[runnervm76f27:06879] *** End of error message ***
</pre>
{% endraw %}
