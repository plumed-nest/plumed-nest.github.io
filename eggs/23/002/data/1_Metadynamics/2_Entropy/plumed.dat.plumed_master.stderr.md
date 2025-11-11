**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/2_Entropy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmw9dnm:07084] *** Process received signal ***
[runnervmw9dnm:07084] Signal: Aborted (6)
[runnervmw9dnm:07084] Signal code:  (-6)
[runnervmw9dnm:07084] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9243845330]
[runnervmw9dnm:07084] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f924389eb2c]
[runnervmw9dnm:07084] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f924384527e]
[runnervmw9dnm:07084] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f92438288ff]
[runnervmw9dnm:07084] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9243ca5ff5]
[runnervmw9dnm:07084] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9243cbb0da]
[runnervmw9dnm:07084] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9243ca5a55]
[runnervmw9dnm:07084] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9243ca5a6f]
[runnervmw9dnm:07084] [ 8] plumed_master(+0x146dd)[0x55a9268ac6dd]
[runnervmw9dnm:07084] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f924382a1ca]
[runnervmw9dnm:07084] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f924382a28b]
[runnervmw9dnm:07084] [11] plumed_master(+0x15365)[0x55a9268ad365]
[runnervmw9dnm:07084] *** End of error message ***
</pre>
{% endraw %}
