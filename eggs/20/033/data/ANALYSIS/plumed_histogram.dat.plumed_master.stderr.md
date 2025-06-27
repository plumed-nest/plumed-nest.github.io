**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  ANALYSIS/plumed_histogram.dat   
Download: [zipped raw stdout](plumed_histogram.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_histogram.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @29 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:69437] *** Process received signal ***
[pkrvmbietmlfzoi:69437] Signal: Aborted (6)
[pkrvmbietmlfzoi:69437] Signal code:  (-6)
[pkrvmbietmlfzoi:69437] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efed5845330]
[pkrvmbietmlfzoi:69437] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efed589eb2c]
[pkrvmbietmlfzoi:69437] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efed584527e]
[pkrvmbietmlfzoi:69437] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efed58288ff]
[pkrvmbietmlfzoi:69437] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efed5ca5ff5]
[pkrvmbietmlfzoi:69437] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efed5cbb0da]
[pkrvmbietmlfzoi:69437] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efed5ca5a55]
[pkrvmbietmlfzoi:69437] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efed5ca5a6f]
[pkrvmbietmlfzoi:69437] [ 8] plumed_master(+0x146dd)[0x561a113416dd]
[pkrvmbietmlfzoi:69437] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efed582a1ca]
[pkrvmbietmlfzoi:69437] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efed582a28b]
[pkrvmbietmlfzoi:69437] [11] plumed_master(+0x15365)[0x561a11342365]
[pkrvmbietmlfzoi:69437] *** End of error message ***
</pre>
{% endraw %}
