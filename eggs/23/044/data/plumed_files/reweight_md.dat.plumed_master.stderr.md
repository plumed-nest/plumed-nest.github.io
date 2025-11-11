**Project ID:** [plumID:23.044]({{ '/' | absolute_url }}eggs/23/044/)  
Stderr for source:  plumed_files/reweight_md.dat   
Download: [zipped raw stdout](reweight_md.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweight_md.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @22 : keyword ARG is compulsory for this action
[runnervmw9dnm:07782] *** Process received signal ***
[runnervmw9dnm:07782] Signal: Aborted (6)
[runnervmw9dnm:07782] Signal code:  (-6)
[runnervmw9dnm:07782] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3268245330]
[runnervmw9dnm:07782] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f326829eb2c]
[runnervmw9dnm:07782] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f326824527e]
[runnervmw9dnm:07782] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f32682288ff]
[runnervmw9dnm:07782] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f32686a5ff5]
[runnervmw9dnm:07782] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f32686bb0da]
[runnervmw9dnm:07782] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f32686a5a55]
[runnervmw9dnm:07782] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f32686a5a6f]
[runnervmw9dnm:07782] [ 8] plumed_master(+0x146dd)[0x56202db1f6dd]
[runnervmw9dnm:07782] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f326822a1ca]
[runnervmw9dnm:07782] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f326822a28b]
[runnervmw9dnm:07782] [11] plumed_master(+0x15365)[0x56202db20365]
[runnervmw9dnm:07782] *** End of error message ***
</pre>
{% endraw %}
