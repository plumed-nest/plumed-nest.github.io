**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  5FU/iMetaD_Input/plumed_imetad.dat   
Download: [zipped raw stdout](plumed_imetad.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_imetad.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PATH with label @s13 : keyword LAMBDA is compulsory for this action
[runnervmw9dnm:07848] *** Process received signal ***
[runnervmw9dnm:07848] Signal: Aborted (6)
[runnervmw9dnm:07848] Signal code:  (-6)
[runnervmw9dnm:07848] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0d16645330]
[runnervmw9dnm:07848] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0d1669eb2c]
[runnervmw9dnm:07848] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0d1664527e]
[runnervmw9dnm:07848] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0d166288ff]
[runnervmw9dnm:07848] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0d16aa5ff5]
[runnervmw9dnm:07848] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0d16abb0da]
[runnervmw9dnm:07848] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0d16aa5a55]
[runnervmw9dnm:07848] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0d16aa5a6f]
[runnervmw9dnm:07848] [ 8] plumed_master(+0x146dd)[0x563c816466dd]
[runnervmw9dnm:07848] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0d1662a1ca]
[runnervmw9dnm:07848] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0d1662a28b]
[runnervmw9dnm:07848] [11] plumed_master(+0x15365)[0x563c81647365]
[runnervmw9dnm:07848] *** End of error message ***
</pre>
{% endraw %}
