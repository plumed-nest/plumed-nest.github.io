**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_forward.dat   
Download: [zipped raw stdout](plumed_Argon_forward.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_forward.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[runnervm76f27:06894] *** Process received signal ***
[runnervm76f27:06894] Signal: Aborted (6)
[runnervm76f27:06894] Signal code:  (-6)
[runnervm76f27:06894] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7126245330]
[runnervm76f27:06894] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f712629ec0c]
[runnervm76f27:06894] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f712624527e]
[runnervm76f27:06894] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f71262288ff]
[runnervm76f27:06894] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f71266a5ff5]
[runnervm76f27:06894] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f71266bb0da]
[runnervm76f27:06894] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f71266a5a55]
[runnervm76f27:06894] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f71266a5a6f]
[runnervm76f27:06894] [ 8] plumed_master(+0x146dd)[0x562bca2276dd]
[runnervm76f27:06894] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f712622a1ca]
[runnervm76f27:06894] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f712622a28b]
[runnervm76f27:06894] [11] plumed_master(+0x15365)[0x562bca228365]
[runnervm76f27:06894] *** End of error message ***
</pre>
{% endraw %}
