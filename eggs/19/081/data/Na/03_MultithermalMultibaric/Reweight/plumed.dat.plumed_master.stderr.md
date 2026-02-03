**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/Reweight/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @29 : keyword ARG is compulsory for this action
[runnervmkj6or:10963] *** Process received signal ***
[runnervmkj6or:10963] Signal: Aborted (6)
[runnervmkj6or:10963] Signal code:  (-6)
[runnervmkj6or:10963] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4fca245330]
[runnervmkj6or:10963] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4fca29eb2c]
[runnervmkj6or:10963] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4fca24527e]
[runnervmkj6or:10963] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4fca2288ff]
[runnervmkj6or:10963] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4fca6a5ff5]
[runnervmkj6or:10963] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4fca6bb0da]
[runnervmkj6or:10963] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4fca6a5a55]
[runnervmkj6or:10963] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4fca6a5a6f]
[runnervmkj6or:10963] [ 8] plumed_master(+0x146dd)[0x555eae04e6dd]
[runnervmkj6or:10963] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4fca22a1ca]
[runnervmkj6or:10963] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4fca22a28b]
[runnervmkj6or:10963] [11] plumed_master(+0x15365)[0x555eae04f365]
[runnervmkj6or:10963] *** End of error message ***
</pre>
{% endraw %}
