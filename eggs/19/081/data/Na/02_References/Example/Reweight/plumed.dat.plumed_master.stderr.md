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
[runnervmw9dnm:10477] *** Process received signal ***
[runnervmw9dnm:10477] Signal: Aborted (6)
[runnervmw9dnm:10477] Signal code:  (-6)
[runnervmw9dnm:10477] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f473bc45330]
[runnervmw9dnm:10477] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f473bc9eb2c]
[runnervmw9dnm:10477] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f473bc4527e]
[runnervmw9dnm:10477] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f473bc288ff]
[runnervmw9dnm:10477] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f473c0a5ff5]
[runnervmw9dnm:10477] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f473c0bb0da]
[runnervmw9dnm:10477] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f473c0a5a55]
[runnervmw9dnm:10477] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f473c0a5a6f]
[runnervmw9dnm:10477] [ 8] plumed_master(+0x146dd)[0x562a118d86dd]
[runnervmw9dnm:10477] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f473bc2a1ca]
[runnervmw9dnm:10477] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f473bc2a28b]
[runnervmw9dnm:10477] [11] plumed_master(+0x15365)[0x562a118d9365]
[runnervmw9dnm:10477] *** End of error message ***
</pre>
{% endraw %}
