library gradle

allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
dependencies {
	        implementation 'com.github.zamnarofiq1:ZamnaLib:1.3'
	}
