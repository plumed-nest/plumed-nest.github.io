**Project ID:** [plumID:25.029]({{ '/' | absolute_url }}eggs/25/029/)  
Stderr for source:  ./crys/4-reweight_crys.dat   
Download: [zipped raw stdout](4-reweight_crys.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](4-reweight_crys.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @46 : keyword ARG is compulsory for this action
[runnervmw9dnm:05789] *** Process received signal ***
[runnervmw9dnm:05789] Signal: Aborted (6)
[runnervmw9dnm:05789] Signal code:  (-6)
[runnervmw9dnm:05789] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f472c645330]
[runnervmw9dnm:05789] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f472c69eb2c]
[runnervmw9dnm:05789] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f472c64527e]
[runnervmw9dnm:05789] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f472c6288ff]
[runnervmw9dnm:05789] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f472caa5ff5]
[runnervmw9dnm:05789] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f472cabb0da]
[runnervmw9dnm:05789] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f472caa5a55]
[runnervmw9dnm:05789] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f472caa5a6f]
[runnervmw9dnm:05789] [ 8] plumed_master(+0x146dd)[0x56244b4b86dd]
[runnervmw9dnm:05789] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f472c62a1ca]
[runnervmw9dnm:05789] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f472c62a28b]
[runnervmw9dnm:05789] [11] plumed_master(+0x15365)[0x56244b4b9365]
[runnervmw9dnm:05789] *** End of error message ***
</pre>
{% endraw %}
