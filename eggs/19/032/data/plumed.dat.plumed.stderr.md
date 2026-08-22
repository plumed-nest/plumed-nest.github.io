**Project ID:** [plumID:19.032]({{ '/' | absolute_url }}eggs/19/032/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PDB2CONSTANT with label @s95 : argument O1O_lessthan was not set in pdb input
[runnervm76f27:11683] *** Process received signal ***
[runnervm76f27:11683] Signal: Aborted (6)
[runnervm76f27:11683] Signal code:  (-6)
[runnervm76f27:11683] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa67d245330]
[runnervm76f27:11683] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa67d29ec0c]
[runnervm76f27:11683] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa67d24527e]
[runnervm76f27:11683] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa67d2288ff]
[runnervm76f27:11683] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa67d6a5ff5]
[runnervm76f27:11683] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa67d6bb0da]
[runnervm76f27:11683] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa67d6a5a55]
[runnervm76f27:11683] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa67d6a5a6f]
[runnervm76f27:11683] [ 8] plumed(+0x146dd)[0x559e22bc76dd]
[runnervm76f27:11683] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa67d22a1ca]
[runnervm76f27:11683] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa67d22a28b]
[runnervm76f27:11683] [11] plumed(+0x15365)[0x559e22bc8365]
[runnervm76f27:11683] *** End of error message ***
</pre>
{% endraw %}
