apply plugin: 'com.android.application'

android {
    compileSdkVersion 22
        buildToolsVersion "22.0.0"

	    defaultConfig {
	            applicationId "com.example.android.rouxcatalog"
		            minSdkVersion 15
			            targetSdkVersion 22
				            versionCode 1
					            versionName "1.0"
						        }
							    buildTypes {
							            release {
								                minifyEnabled false
										            proguardFiles getDefaultProguardFile('proguard-android.txt'), 'proguard-rules.pro'
											            }
												        }
													}

													dependencies {
													    compile fileTree(dir: 'libs', include: ['*.jar'])
													        compile 'com.android.support:appcompat-v7:22.1.1'
														}

