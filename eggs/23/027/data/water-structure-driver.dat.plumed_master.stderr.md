**Project ID:** [plumID:23.027]({{ '/' | absolute_url }}eggs/23/027/)  
Stderr for source:  water-structure-driver.dat   
Download: [zipped raw stdout](water-structure-driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](water-structure-driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @149 : keyword ARG is compulsory for this action
[runnervmw9dnm:07825] *** Process received signal ***
[runnervmw9dnm:07825] Signal: Aborted (6)
[runnervmw9dnm:07825] Signal code:  (-6)
[runnervmw9dnm:07825] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa38ca45330]
[runnervmw9dnm:07825] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa38ca9eb2c]
[runnervmw9dnm:07825] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa38ca4527e]
[runnervmw9dnm:07825] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa38ca288ff]
[runnervmw9dnm:07825] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa38cea5ff5]
[runnervmw9dnm:07825] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa38cebb0da]
[runnervmw9dnm:07825] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa38cea5a55]
[runnervmw9dnm:07825] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa38cea5a6f]
[runnervmw9dnm:07825] [ 8] plumed_master(+0x146dd)[0x55a28ce976dd]
[runnervmw9dnm:07825] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa38ca2a1ca]
[runnervmw9dnm:07825] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa38ca2a28b]
[runnervmw9dnm:07825] [11] plumed_master(+0x15365)[0x55a28ce98365]
[runnervmw9dnm:07825] *** End of error message ***
</pre>
{% endraw %}
