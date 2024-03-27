**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:986) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&, const bool&)
ERROR
I cannot understand line: PYTHONFUNCTION LABEL=dAB2 ARG=dAB IMPORT=pythonfunction FUNCTION=square PERIODIC=NO
Maybe a missing space or a typo?
[fv-az985-228:69917] *** Process received signal ***
[fv-az985-228:69917] Signal: Aborted (6)
[fv-az985-228:69917] Signal code:  (-6)
[fv-az985-228:69917] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f8a20842520]
[fv-az985-228:69917] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f8a208969fc]
[fv-az985-228:69917] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f8a20842476]
[fv-az985-228:69917] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f8a208287f3]
[fv-az985-228:69917] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f8a20ca4f26]
[fv-az985-228:69917] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f8a20cb6d9c]
[fv-az985-228:69917] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f8a20cb6e07]
[fv-az985-228:69917] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f8a20cb70bb]
[fv-az985-228:69917] [ 8] plumed_master(+0x12e7f)[0x5646bd596e7f]
[fv-az985-228:69917] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f8a20829d90]
[fv-az985-228:69917] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f8a20829e40]
[fv-az985-228:69917] [11] plumed_master(+0x13115)[0x5646bd597115]
[fv-az985-228:69917] *** End of error message ***
</pre>
{% endraw %}
