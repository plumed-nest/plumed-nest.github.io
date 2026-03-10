**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_forward.dat   
Download: [zipped raw stdout](plumed_Argon_forward.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_forward.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[runnervm0kj6c:04690] *** Process received signal ***
[runnervm0kj6c:04690] Signal: Aborted (6)
[runnervm0kj6c:04690] Signal code:  (-6)
[runnervm0kj6c:04690] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fec1da45330]
[runnervm0kj6c:04690] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fec1da9eb2c]
[runnervm0kj6c:04690] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fec1da4527e]
[runnervm0kj6c:04690] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fec1da288ff]
[runnervm0kj6c:04690] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fec1dea5ff5]
[runnervm0kj6c:04690] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fec1debb0da]
[runnervm0kj6c:04690] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fec1dea5a55]
[runnervm0kj6c:04690] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fec1dea5a6f]
[runnervm0kj6c:04690] [ 8] plumed_master(+0x146dd)[0x55f436f1a6dd]
[runnervm0kj6c:04690] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fec1da2a1ca]
[runnervm0kj6c:04690] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fec1da2a28b]
[runnervm0kj6c:04690] [11] plumed_master(+0x15365)[0x55f436f1b365]
[runnervm0kj6c:04690] *** End of error message ***
</pre>
{% endraw %}
