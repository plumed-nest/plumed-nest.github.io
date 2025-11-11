**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PRINT with label @333 : cannot use argument parabeta0_both.struct-1 in input as not all elements are computed
[runnervmw9dnm:06083] *** Process received signal ***
[runnervmw9dnm:06083] Signal: Aborted (6)
[runnervmw9dnm:06083] Signal code:  (-6)
[runnervmw9dnm:06083] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f355f645330]
[runnervmw9dnm:06083] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f355f69eb2c]
[runnervmw9dnm:06083] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f355f64527e]
[runnervmw9dnm:06083] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f355f6288ff]
[runnervmw9dnm:06083] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f355faa5ff5]
[runnervmw9dnm:06083] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f355fabb0da]
[runnervmw9dnm:06083] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f355faa5a55]
[runnervmw9dnm:06083] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f355faa5a6f]
[runnervmw9dnm:06083] [ 8] plumed_master(+0x146dd)[0x55804ceed6dd]
[runnervmw9dnm:06083] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f355f62a1ca]
[runnervmw9dnm:06083] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f355f62a28b]
[runnervmw9dnm:06083] [11] plumed_master(+0x15365)[0x55804ceee365]
[runnervmw9dnm:06083] *** End of error message ***
</pre>
{% endraw %}
