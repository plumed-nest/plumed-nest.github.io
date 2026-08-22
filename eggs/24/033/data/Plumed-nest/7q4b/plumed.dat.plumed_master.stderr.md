**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[runnervm76f27:05965] *** Process received signal ***
[runnervm76f27:05965] Signal: Aborted (6)
[runnervm76f27:05965] Signal code:  (-6)
[runnervm76f27:05965] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4b36445330]
[runnervm76f27:05965] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4b3649ec0c]
[runnervm76f27:05965] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4b3644527e]
[runnervm76f27:05965] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4b364288ff]
[runnervm76f27:05965] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4b368a5ff5]
[runnervm76f27:05965] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4b368bb0da]
[runnervm76f27:05965] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4b368a5a55]
[runnervm76f27:05965] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4b368a5a6f]
[runnervm76f27:05965] [ 8] plumed_master(+0x146dd)[0x5641236cb6dd]
[runnervm76f27:05965] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4b3642a1ca]
[runnervm76f27:05965] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4b3642a28b]
[runnervm76f27:05965] [11] plumed_master(+0x15365)[0x5641236cc365]
[runnervm76f27:05965] *** End of error message ***
</pre>
{% endraw %}
