**Project ID:** [plumID:19.044]({{ '/' | absolute_url }}eggs/19/044/)  
Stderr for source:  MultithermalMultibaricSimulations/MultithermalMultibaric/Analysis/SampledDistribution/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @29 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:37979] *** Process received signal ***
[pkrvmf6wy0o8zjz:37979] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:37979] Signal code:  (-6)
[pkrvmf6wy0o8zjz:37979] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5244c45330]
[pkrvmf6wy0o8zjz:37979] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5244c9eb2c]
[pkrvmf6wy0o8zjz:37979] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5244c4527e]
[pkrvmf6wy0o8zjz:37979] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5244c288ff]
[pkrvmf6wy0o8zjz:37979] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f52450a5ff5]
[pkrvmf6wy0o8zjz:37979] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f52450bb0da]
[pkrvmf6wy0o8zjz:37979] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f52450a5a55]
[pkrvmf6wy0o8zjz:37979] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f52450a5a6f]
[pkrvmf6wy0o8zjz:37979] [ 8] plumed_master(+0x146dd)[0x5620af6746dd]
[pkrvmf6wy0o8zjz:37979] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5244c2a1ca]
[pkrvmf6wy0o8zjz:37979] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5244c2a28b]
[pkrvmf6wy0o8zjz:37979] [11] plumed_master(+0x15365)[0x5620af675365]
[pkrvmf6wy0o8zjz:37979] *** End of error message ***
</pre>
{% endraw %}
