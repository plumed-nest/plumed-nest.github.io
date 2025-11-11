**Project ID:** [plumID:19.043]({{ '/' | absolute_url }}eggs/19/043/)  
Stderr for source:  3_class/meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervmw9dnm:12085] *** Process received signal ***
[runnervmw9dnm:12085] Signal: Aborted (6)
[runnervmw9dnm:12085] Signal code:  (-6)
[runnervmw9dnm:12085] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6201845330]
[runnervmw9dnm:12085] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f620189eb2c]
[runnervmw9dnm:12085] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f620184527e]
[runnervmw9dnm:12085] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f62018288ff]
[runnervmw9dnm:12085] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6201ca5ff5]
[runnervmw9dnm:12085] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6201cbb0da]
[runnervmw9dnm:12085] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6201ca5a55]
[runnervmw9dnm:12085] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6201ca5a6f]
[runnervmw9dnm:12085] [ 8] plumed_master(+0x146dd)[0x55fa5f7f76dd]
[runnervmw9dnm:12085] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f620182a1ca]
[runnervmw9dnm:12085] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f620182a28b]
[runnervmw9dnm:12085] [11] plumed_master(+0x15365)[0x55fa5f7f8365]
[runnervmw9dnm:12085] *** End of error message ***
</pre>
{% endraw %}
