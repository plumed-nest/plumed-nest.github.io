**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/1_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmw9dnm:07031] *** Process received signal ***
[runnervmw9dnm:07031] Signal: Aborted (6)
[runnervmw9dnm:07031] Signal code:  (-6)
[runnervmw9dnm:07031] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8ee3045330]
[runnervmw9dnm:07031] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8ee309eb2c]
[runnervmw9dnm:07031] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8ee304527e]
[runnervmw9dnm:07031] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8ee30288ff]
[runnervmw9dnm:07031] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8ee34a5ff5]
[runnervmw9dnm:07031] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8ee34bb0da]
[runnervmw9dnm:07031] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8ee34a5a55]
[runnervmw9dnm:07031] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8ee34a5a6f]
[runnervmw9dnm:07031] [ 8] plumed_master(+0x146dd)[0x5588dbfb46dd]
[runnervmw9dnm:07031] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8ee302a1ca]
[runnervmw9dnm:07031] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8ee302a28b]
[runnervmw9dnm:07031] [11] plumed_master(+0x15365)[0x5588dbfb5365]
[runnervmw9dnm:07031] *** End of error message ***
</pre>
{% endraw %}
