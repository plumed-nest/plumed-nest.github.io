**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT/plumed_h1h2.dat   
Download: [zipped raw stdout](plumed_h1h2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_h1h2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @38 : keyword ARG is compulsory for this action
[runnervm76f27:04723] *** Process received signal ***
[runnervm76f27:04723] Signal: Aborted (6)
[runnervm76f27:04723] Signal code:  (-6)
[runnervm76f27:04723] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa3c8845330]
[runnervm76f27:04723] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa3c889ec0c]
[runnervm76f27:04723] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa3c884527e]
[runnervm76f27:04723] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa3c88288ff]
[runnervm76f27:04723] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa3c8ca5ff5]
[runnervm76f27:04723] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa3c8cbb0da]
[runnervm76f27:04723] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa3c8ca5a55]
[runnervm76f27:04723] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa3c8ca5a6f]
[runnervm76f27:04723] [ 8] plumed_master(+0x146dd)[0x564705dd86dd]
[runnervm76f27:04723] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa3c882a1ca]
[runnervm76f27:04723] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa3c882a28b]
[runnervm76f27:04723] [11] plumed_master(+0x15365)[0x564705dd9365]
[runnervm76f27:04723] *** End of error message ***
</pre>
{% endraw %}
