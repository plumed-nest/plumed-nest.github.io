**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/bend-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @50 : keyword ARG is compulsory for this action
[runnervmvrwv9:08480] *** Process received signal ***
[runnervmvrwv9:08480] Signal: Aborted (6)
[runnervmvrwv9:08480] Signal code:  (-6)
[runnervmvrwv9:08480] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f34fb845330]
[runnervmvrwv9:08480] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f34fb89eb2c]
[runnervmvrwv9:08480] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f34fb84527e]
[runnervmvrwv9:08480] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f34fb8288ff]
[runnervmvrwv9:08480] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f34fbca5ff5]
[runnervmvrwv9:08480] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f34fbcbb0da]
[runnervmvrwv9:08480] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f34fbca5a55]
[runnervmvrwv9:08480] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f34fbca5a6f]
[runnervmvrwv9:08480] [ 8] plumed_master(+0x146dd)[0x555d8e4936dd]
[runnervmvrwv9:08480] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f34fb82a1ca]
[runnervmvrwv9:08480] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f34fb82a28b]
[runnervmvrwv9:08480] [11] plumed_master(+0x15365)[0x555d8e494365]
[runnervmvrwv9:08480] *** End of error message ***
</pre>
{% endraw %}
