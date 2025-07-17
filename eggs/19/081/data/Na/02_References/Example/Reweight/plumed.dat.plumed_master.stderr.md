**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/Reweight/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @33 : keyword ARG is compulsory for this action
[pkrvmq0rgcvqdmg:11392] *** Process received signal ***
[pkrvmq0rgcvqdmg:11392] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:11392] Signal code:  (-6)
[pkrvmq0rgcvqdmg:11392] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efc96845330]
[pkrvmq0rgcvqdmg:11392] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efc9689eb2c]
[pkrvmq0rgcvqdmg:11392] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efc9684527e]
[pkrvmq0rgcvqdmg:11392] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efc968288ff]
[pkrvmq0rgcvqdmg:11392] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efc96ca5ff5]
[pkrvmq0rgcvqdmg:11392] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efc96cbb0da]
[pkrvmq0rgcvqdmg:11392] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efc96ca5a55]
[pkrvmq0rgcvqdmg:11392] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efc96ca5a6f]
[pkrvmq0rgcvqdmg:11392] [ 8] plumed_master(+0x146dd)[0x5558a2ac76dd]
[pkrvmq0rgcvqdmg:11392] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efc9682a1ca]
[pkrvmq0rgcvqdmg:11392] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efc9682a28b]
[pkrvmq0rgcvqdmg:11392] [11] plumed_master(+0x15365)[0x5558a2ac8365]
[pkrvmq0rgcvqdmg:11392] *** End of error message ***
</pre>
{% endraw %}
