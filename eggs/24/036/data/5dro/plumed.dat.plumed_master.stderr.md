**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  5dro/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @20 : keyword ARG is compulsory for this action
[runnervmvrwv9:04632] *** Process received signal ***
[runnervmvrwv9:04632] Signal: Aborted (6)
[runnervmvrwv9:04632] Signal code:  (-6)
[runnervmvrwv9:04632] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff806645330]
[runnervmvrwv9:04632] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff80669eb2c]
[runnervmvrwv9:04632] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff80664527e]
[runnervmvrwv9:04632] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff8066288ff]
[runnervmvrwv9:04632] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff806aa5ff5]
[runnervmvrwv9:04632] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff806abb0da]
[runnervmvrwv9:04632] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff806aa5a55]
[runnervmvrwv9:04632] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff806aa5a6f]
[runnervmvrwv9:04632] [ 8] plumed_master(+0x146dd)[0x5631d497f6dd]
[runnervmvrwv9:04632] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff80662a1ca]
[runnervmvrwv9:04632] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff80662a28b]
[runnervmvrwv9:04632] [11] plumed_master(+0x15365)[0x5631d4980365]
[runnervmvrwv9:04632] *** End of error message ***
</pre>
{% endraw %}
