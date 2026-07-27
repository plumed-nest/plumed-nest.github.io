**Project ID:** [plumID:23.044]({{ '/' | absolute_url }}eggs/23/044/)  
Stderr for source:  plumed_files/reweight_md.dat   
Download: [zipped raw stdout](reweight_md.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweight_md.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @22 : keyword ARG is compulsory for this action
[runnervmvrwv9:06159] *** Process received signal ***
[runnervmvrwv9:06159] Signal: Aborted (6)
[runnervmvrwv9:06159] Signal code:  (-6)
[runnervmvrwv9:06159] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4bdd445330]
[runnervmvrwv9:06159] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4bdd49eb2c]
[runnervmvrwv9:06159] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4bdd44527e]
[runnervmvrwv9:06159] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4bdd4288ff]
[runnervmvrwv9:06159] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4bdd8a5ff5]
[runnervmvrwv9:06159] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4bdd8bb0da]
[runnervmvrwv9:06159] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4bdd8a5a55]
[runnervmvrwv9:06159] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4bdd8a5a6f]
[runnervmvrwv9:06159] [ 8] plumed_master(+0x146dd)[0x55c9ae0186dd]
[runnervmvrwv9:06159] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4bdd42a1ca]
[runnervmvrwv9:06159] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4bdd42a28b]
[runnervmvrwv9:06159] [11] plumed_master(+0x15365)[0x55c9ae019365]
[runnervmvrwv9:06159] *** End of error message ***
</pre>
{% endraw %}
