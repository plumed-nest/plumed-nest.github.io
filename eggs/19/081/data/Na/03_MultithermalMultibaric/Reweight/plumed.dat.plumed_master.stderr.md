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
[runnervmw9dnm:10686] *** Process received signal ***
[runnervmw9dnm:10686] Signal: Aborted (6)
[runnervmw9dnm:10686] Signal code:  (-6)
[runnervmw9dnm:10686] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7d28e45330]
[runnervmw9dnm:10686] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7d28e9eb2c]
[runnervmw9dnm:10686] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7d28e4527e]
[runnervmw9dnm:10686] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7d28e288ff]
[runnervmw9dnm:10686] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7d292a5ff5]
[runnervmw9dnm:10686] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7d292bb0da]
[runnervmw9dnm:10686] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7d292a5a55]
[runnervmw9dnm:10686] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7d292a5a6f]
[runnervmw9dnm:10686] [ 8] plumed_master(+0x146dd)[0x55751c1b76dd]
[runnervmw9dnm:10686] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7d28e2a1ca]
[runnervmw9dnm:10686] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7d28e2a28b]
[runnervmw9dnm:10686] [11] plumed_master(+0x15365)[0x55751c1b8365]
[runnervmw9dnm:10686] *** End of error message ***
</pre>
{% endraw %}
