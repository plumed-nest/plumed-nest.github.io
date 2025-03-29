**Project ID:** [plumID:19.027]({{ '/' | absolute_url }}eggs/19/027/)  
Stderr for source:  MulticanonicalSimulations/References/Temp550K/Distribution/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @28 : keyword ARG is compulsory for this action
[fv-az789-879:68519] *** Process received signal ***
[fv-az789-879:68519] Signal: Aborted (6)
[fv-az789-879:68519] Signal code:  (-6)
[fv-az789-879:68519] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f50ae245330]
[fv-az789-879:68519] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f50ae29eb2c]
[fv-az789-879:68519] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f50ae24527e]
[fv-az789-879:68519] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f50ae2288ff]
[fv-az789-879:68519] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f50ae6a5ff5]
[fv-az789-879:68519] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f50ae6bb0da]
[fv-az789-879:68519] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f50ae6a5a55]
[fv-az789-879:68519] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f50ae6a5a6f]
[fv-az789-879:68519] [ 8] plumed_master(+0x146dd)[0x55a16596a6dd]
[fv-az789-879:68519] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f50ae22a1ca]
[fv-az789-879:68519] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f50ae22a28b]
[fv-az789-879:68519] [11] plumed_master(+0x15365)[0x55a16596b365]
[fv-az789-879:68519] *** End of error message ***
</pre>
{% endraw %}
