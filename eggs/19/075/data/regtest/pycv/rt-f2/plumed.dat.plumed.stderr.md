**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: PYTHONFUNCTION LABEL=cc1 ARG=t1,t2,t3 IMPORT=pythonfunction FUNCTION=cc1 PERIODIC=NO
Maybe a missing space or a typo?
[fv-az985-228:69940] *** Process received signal ***
[fv-az985-228:69940] Signal: Aborted (6)
[fv-az985-228:69940] Signal code:  (-6)
[fv-az985-228:69940] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fbd1fa42520]
[fv-az985-228:69940] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fbd1fa969fc]
[fv-az985-228:69940] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fbd1fa42476]
[fv-az985-228:69940] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fbd1fa287f3]
[fv-az985-228:69940] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fbd1fea4f26]
[fv-az985-228:69940] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fbd1feb6d9c]
[fv-az985-228:69940] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fbd1feb6e07]
[fv-az985-228:69940] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fbd1feb70bb]
[fv-az985-228:69940] [ 8] plumed(+0x12f48)[0x55986609cf48]
[fv-az985-228:69940] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fbd1fa29d90]
[fv-az985-228:69940] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fbd1fa29e40]
[fv-az985-228:69940] [11] plumed(+0x131e5)[0x55986609d1e5]
[fv-az985-228:69940] *** End of error message ***
</pre>
{% endraw %}
