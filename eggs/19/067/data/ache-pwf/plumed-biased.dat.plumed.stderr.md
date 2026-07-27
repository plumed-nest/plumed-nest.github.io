**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pwf/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervmvrwv9:10287] *** Process received signal ***
[runnervmvrwv9:10287] Signal: Aborted (6)
[runnervmvrwv9:10287] Signal code:  (-6)
[runnervmvrwv9:10287] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f65ec645330]
[runnervmvrwv9:10287] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f65ec69eb2c]
[runnervmvrwv9:10287] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f65ec64527e]
[runnervmvrwv9:10287] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f65ec6288ff]
[runnervmvrwv9:10287] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f65ecaa5ff5]
[runnervmvrwv9:10287] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f65ecabb0da]
[runnervmvrwv9:10287] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f65ecaa5a55]
[runnervmvrwv9:10287] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f65ecaa5a6f]
[runnervmvrwv9:10287] [ 8] plumed(+0x146dd)[0x55cc1629d6dd]
[runnervmvrwv9:10287] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f65ec62a1ca]
[runnervmvrwv9:10287] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f65ec62a28b]
[runnervmvrwv9:10287] [11] plumed(+0x15365)[0x55cc1629e365]
[runnervmvrwv9:10287] *** End of error message ***
</pre>
{% endraw %}
