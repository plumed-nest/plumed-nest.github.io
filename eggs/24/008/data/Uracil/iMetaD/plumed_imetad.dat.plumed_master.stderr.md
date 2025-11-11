**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Uracil/iMetaD/plumed_imetad.dat   
Download: [zipped raw stdout](plumed_imetad.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_imetad.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PATH with label @s13 : keyword LAMBDA is compulsory for this action
[runnervmw9dnm:08014] *** Process received signal ***
[runnervmw9dnm:08014] Signal: Aborted (6)
[runnervmw9dnm:08014] Signal code:  (-6)
[runnervmw9dnm:08014] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe976245330]
[runnervmw9dnm:08014] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe97629eb2c]
[runnervmw9dnm:08014] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe97624527e]
[runnervmw9dnm:08014] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe9762288ff]
[runnervmw9dnm:08014] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe9766a5ff5]
[runnervmw9dnm:08014] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe9766bb0da]
[runnervmw9dnm:08014] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe9766a5a55]
[runnervmw9dnm:08014] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe9766a5a6f]
[runnervmw9dnm:08014] [ 8] plumed_master(+0x146dd)[0x555754f306dd]
[runnervmw9dnm:08014] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe97622a1ca]
[runnervmw9dnm:08014] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe97622a28b]
[runnervmw9dnm:08014] [11] plumed_master(+0x15365)[0x555754f31365]
[runnervmw9dnm:08014] *** End of error message ***
</pre>
{% endraw %}
