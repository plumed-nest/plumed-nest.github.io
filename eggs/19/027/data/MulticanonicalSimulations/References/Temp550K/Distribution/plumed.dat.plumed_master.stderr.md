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
[fv-az1267-279:66135] *** Process received signal ***
[fv-az1267-279:66135] Signal: Aborted (6)
[fv-az1267-279:66135] Signal code:  (-6)
[fv-az1267-279:66135] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6541045330]
[fv-az1267-279:66135] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f654109eb2c]
[fv-az1267-279:66135] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f654104527e]
[fv-az1267-279:66135] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f65410288ff]
[fv-az1267-279:66135] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f65414a5ff5]
[fv-az1267-279:66135] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f65414bb0da]
[fv-az1267-279:66135] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f65414a5a55]
[fv-az1267-279:66135] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f65414a5a6f]
[fv-az1267-279:66135] [ 8] plumed_master(+0x146dd)[0x560df47696dd]
[fv-az1267-279:66135] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f654102a1ca]
[fv-az1267-279:66135] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f654102a28b]
[fv-az1267-279:66135] [11] plumed_master(+0x15365)[0x560df476a365]
[fv-az1267-279:66135] *** End of error message ***
</pre>
{% endraw %}
