**Project ID:** [plumID:20.000]({{ '/' | absolute_url }}eggs/20/000/)  
Stderr for source:  reweighting/reweighting.dat   
Download: [zipped raw stdout](reweighting.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweighting.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @20 : keyword ARG is compulsory for this action
[runnervmeorf1:10652] *** Process received signal ***
[runnervmeorf1:10652] Signal: Aborted (6)
[runnervmeorf1:10652] Signal code:  (-6)
[runnervmeorf1:10652] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f39ce445330]
[runnervmeorf1:10652] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f39ce49eb2c]
[runnervmeorf1:10652] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f39ce44527e]
[runnervmeorf1:10652] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f39ce4288ff]
[runnervmeorf1:10652] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f39ce8a5ff5]
[runnervmeorf1:10652] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f39ce8bb0da]
[runnervmeorf1:10652] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f39ce8a5a55]
[runnervmeorf1:10652] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f39ce8a5a6f]
[runnervmeorf1:10652] [ 8] plumed_master(+0x146dd)[0x56037c1306dd]
[runnervmeorf1:10652] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f39ce42a1ca]
[runnervmeorf1:10652] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f39ce42a28b]
[runnervmeorf1:10652] [11] plumed_master(+0x15365)[0x56037c131365]
[runnervmeorf1:10652] *** End of error message ***
</pre>
{% endraw %}
