**Project ID:** [plumID:23.027]({{ '/' | absolute_url }}eggs/23/027/)  
Stderr for source:  ion-structure-driver.dat   
Download: [zipped raw stdout](ion-structure-driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](ion-structure-driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs0l : keyword ARG is compulsory for this action
[runnervm76f27:07630] *** Process received signal ***
[runnervm76f27:07630] Signal: Aborted (6)
[runnervm76f27:07630] Signal code:  (-6)
[runnervm76f27:07630] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f29d1845330]
[runnervm76f27:07630] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f29d189ec0c]
[runnervm76f27:07630] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f29d184527e]
[runnervm76f27:07630] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f29d18288ff]
[runnervm76f27:07630] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f29d1ca5ff5]
[runnervm76f27:07630] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f29d1cbb0da]
[runnervm76f27:07630] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f29d1ca5a55]
[runnervm76f27:07630] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f29d1ca5a6f]
[runnervm76f27:07630] [ 8] plumed_master(+0x146dd)[0x561d9840d6dd]
[runnervm76f27:07630] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f29d182a1ca]
[runnervm76f27:07630] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f29d182a28b]
[runnervm76f27:07630] [11] plumed_master(+0x15365)[0x561d9840e365]
[runnervm76f27:07630] *** End of error message ***
</pre>
{% endraw %}
