**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action WHOLEMOLECULES with label @5 : cannot understand the following words from the input line : REF0, REF1, REF2
[runnervm76f27:09098] *** Process received signal ***
[runnervm76f27:09098] Signal: Aborted (6)
[runnervm76f27:09098] Signal code:  (-6)
[runnervm76f27:09098] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa427045330]
[runnervm76f27:09098] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa42709ec0c]
[runnervm76f27:09098] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa42704527e]
[runnervm76f27:09098] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa4270288ff]
[runnervm76f27:09098] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa4274a5ff5]
[runnervm76f27:09098] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa4274bb0da]
[runnervm76f27:09098] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa4274a5a55]
[runnervm76f27:09098] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa4274a5a6f]
[runnervm76f27:09098] [ 8] plumed_master(+0x146dd)[0x55929ecca6dd]
[runnervm76f27:09098] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa42702a1ca]
[runnervm76f27:09098] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa42702a28b]
[runnervm76f27:09098] [11] plumed_master(+0x15365)[0x55929eccb365]
[runnervm76f27:09098] *** End of error message ***
</pre>
{% endraw %}
