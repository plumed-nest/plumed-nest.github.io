**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  DIDE-water/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @46 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:05942] *** Process received signal ***
[pkrvmbietmlfzoi:05942] Signal: Aborted (6)
[pkrvmbietmlfzoi:05942] Signal code:  (-6)
[pkrvmbietmlfzoi:05942] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff89c645330]
[pkrvmbietmlfzoi:05942] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff89c69eb2c]
[pkrvmbietmlfzoi:05942] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff89c64527e]
[pkrvmbietmlfzoi:05942] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff89c6288ff]
[pkrvmbietmlfzoi:05942] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff89caa5ff5]
[pkrvmbietmlfzoi:05942] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff89cabb0da]
[pkrvmbietmlfzoi:05942] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff89caa5a55]
[pkrvmbietmlfzoi:05942] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff89caa5a6f]
[pkrvmbietmlfzoi:05942] [ 8] plumed_master(+0x146dd)[0x560ccf2f26dd]
[pkrvmbietmlfzoi:05942] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff89c62a1ca]
[pkrvmbietmlfzoi:05942] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff89c62a28b]
[pkrvmbietmlfzoi:05942] [11] plumed_master(+0x15365)[0x560ccf2f3365]
[pkrvmbietmlfzoi:05942] *** End of error message ***
</pre>
{% endraw %}
