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
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @23 : keyword ARG is compulsory for this action
[runnervmkj6or:10754] *** Process received signal ***
[runnervmkj6or:10754] Signal: Aborted (6)
[runnervmkj6or:10754] Signal code:  (-6)
[runnervmkj6or:10754] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc7b2845330]
[runnervmkj6or:10754] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc7b289eb2c]
[runnervmkj6or:10754] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc7b284527e]
[runnervmkj6or:10754] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc7b28288ff]
[runnervmkj6or:10754] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc7b2ca5ff5]
[runnervmkj6or:10754] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc7b2cbb0da]
[runnervmkj6or:10754] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc7b2ca5a55]
[runnervmkj6or:10754] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc7b2ca5a6f]
[runnervmkj6or:10754] [ 8] plumed_master(+0x146dd)[0x5557ac0376dd]
[runnervmkj6or:10754] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc7b282a1ca]
[runnervmkj6or:10754] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc7b282a28b]
[runnervmkj6or:10754] [11] plumed_master(+0x15365)[0x5557ac038365]
[runnervmkj6or:10754] *** End of error message ***
</pre>
{% endraw %}
