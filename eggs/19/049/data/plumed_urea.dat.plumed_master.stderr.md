**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX with label @s43 : missing SWITCH11 keyword
[runnervm76f27:11700] *** Process received signal ***
[runnervm76f27:11700] Signal: Aborted (6)
[runnervm76f27:11700] Signal code:  (-6)
[runnervm76f27:11700] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fccff245330]
[runnervm76f27:11700] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fccff29ec0c]
[runnervm76f27:11700] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fccff24527e]
[runnervm76f27:11700] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fccff2288ff]
[runnervm76f27:11700] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fccff6a5ff5]
[runnervm76f27:11700] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fccff6bb0da]
[runnervm76f27:11700] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fccff6a5a55]
[runnervm76f27:11700] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fccff6a5a6f]
[runnervm76f27:11700] [ 8] plumed_master(+0x146dd)[0x557cd9af16dd]
[runnervm76f27:11700] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fccff22a1ca]
[runnervm76f27:11700] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fccff22a28b]
[runnervm76f27:11700] [11] plumed_master(+0x15365)[0x557cd9af2365]
[runnervm76f27:11700] *** End of error message ***
</pre>
{% endraw %}
