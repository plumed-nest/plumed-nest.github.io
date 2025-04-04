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
[fv-az1360-658:12634] *** Process received signal ***
[fv-az1360-658:12634] Signal: Aborted (6)
[fv-az1360-658:12634] Signal code:  (-6)
[fv-az1360-658:12634] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc463845330]
[fv-az1360-658:12634] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc46389eb2c]
[fv-az1360-658:12634] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc46384527e]
[fv-az1360-658:12634] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc4638288ff]
[fv-az1360-658:12634] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc463ca5ff5]
[fv-az1360-658:12634] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc463cbb0da]
[fv-az1360-658:12634] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc463ca5a55]
[fv-az1360-658:12634] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc463ca5a6f]
[fv-az1360-658:12634] [ 8] plumed_master(+0x146dd)[0x55e7d46b26dd]
[fv-az1360-658:12634] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc46382a1ca]
[fv-az1360-658:12634] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc46382a28b]
[fv-az1360-658:12634] [11] plumed_master(+0x15365)[0x55e7d46b3365]
[fv-az1360-658:12634] *** End of error message ***
</pre>
{% endraw %}
