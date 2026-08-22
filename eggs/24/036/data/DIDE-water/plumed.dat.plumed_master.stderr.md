**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  DIDE-water/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @36 : keyword ARG is compulsory for this action
[runnervm76f27:04646] *** Process received signal ***
[runnervm76f27:04646] Signal: Aborted (6)
[runnervm76f27:04646] Signal code:  (-6)
[runnervm76f27:04646] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f65ec845330]
[runnervm76f27:04646] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f65ec89ec0c]
[runnervm76f27:04646] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f65ec84527e]
[runnervm76f27:04646] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f65ec8288ff]
[runnervm76f27:04646] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f65ecca5ff5]
[runnervm76f27:04646] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f65eccbb0da]
[runnervm76f27:04646] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f65ecca5a55]
[runnervm76f27:04646] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f65ecca5a6f]
[runnervm76f27:04646] [ 8] plumed_master(+0x146dd)[0x563ccb27b6dd]
[runnervm76f27:04646] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f65ec82a1ca]
[runnervm76f27:04646] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f65ec82a28b]
[runnervm76f27:04646] [11] plumed_master(+0x15365)[0x563ccb27c365]
[runnervm76f27:04646] *** End of error message ***
</pre>
{% endraw %}
