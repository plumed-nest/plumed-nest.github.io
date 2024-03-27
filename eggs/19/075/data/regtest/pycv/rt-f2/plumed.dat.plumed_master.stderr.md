**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:986) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&, const bool&)
ERROR
I cannot understand line: PYTHONFUNCTION LABEL=cc1 ARG=t1,t2,t3 IMPORT=pythonfunction FUNCTION=cc1 PERIODIC=NO
Maybe a missing space or a typo?
[fv-az985-228:69949] *** Process received signal ***
[fv-az985-228:69949] Signal: Aborted (6)
[fv-az985-228:69949] Signal code:  (-6)
[fv-az985-228:69949] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f236ea42520]
[fv-az985-228:69949] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f236ea969fc]
[fv-az985-228:69949] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f236ea42476]
[fv-az985-228:69949] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f236ea287f3]
[fv-az985-228:69949] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f236eea4f26]
[fv-az985-228:69949] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f236eeb6d9c]
[fv-az985-228:69949] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f236eeb6e07]
[fv-az985-228:69949] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f236eeb70bb]
[fv-az985-228:69949] [ 8] plumed_master(+0x12e7f)[0x55f55865ce7f]
[fv-az985-228:69949] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f236ea29d90]
[fv-az985-228:69949] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f236ea29e40]
[fv-az985-228:69949] [11] plumed_master(+0x13115)[0x55f55865d115]
[fv-az985-228:69949] *** End of error message ***
</pre>
{% endraw %}
