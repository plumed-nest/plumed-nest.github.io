**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/Reweight/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @29 : keyword ARG is compulsory for this action
[runnervm76f27:09856] *** Process received signal ***
[runnervm76f27:09856] Signal: Aborted (6)
[runnervm76f27:09856] Signal code:  (-6)
[runnervm76f27:09856] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f47de045330]
[runnervm76f27:09856] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f47de09ec0c]
[runnervm76f27:09856] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f47de04527e]
[runnervm76f27:09856] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f47de0288ff]
[runnervm76f27:09856] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f47de4a5ff5]
[runnervm76f27:09856] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f47de4bb0da]
[runnervm76f27:09856] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f47de4a5a55]
[runnervm76f27:09856] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f47de4a5a6f]
[runnervm76f27:09856] [ 8] plumed_master(+0x146dd)[0x558b88c916dd]
[runnervm76f27:09856] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f47de02a1ca]
[runnervm76f27:09856] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f47de02a28b]
[runnervm76f27:09856] [11] plumed_master(+0x15365)[0x558b88c92365]
[runnervm76f27:09856] *** End of error message ***
</pre>
{% endraw %}
