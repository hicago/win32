---
Description: 'Enrolls an end user with a certification authority (CA) by using a template, the subject name, and the length, in bits, of the key.'
ms.assetid: 'ee290c78-dbfa-4414-8489-aa886360652b'
title: enrollSimpleUserCert
---

# enrollSimpleUserCert

The enrollSimpleUserCert sample enrolls an end user with a certification authority (CA) by using a template, the subject name, and the length, in bits, of the key.

## Location

When you install the Microsoft Windows Software Development Kit (SDK), a C++ version of the sample is installed, by default, in the *%ProgramFiles%*\\Microsoft SDKs\\Windows\\v7.0\\Samples\\Security\\X509 Certificate Enrollment\\VC\\enrollSimpleUserCert folder. A C# version is installed in the *%ProgramFiles%*\\Microsoft SDKs\\Windows\\v7.0\\Samples\\X509 Certificate Enrollment\\CSharp\\EnrollSimpleUserCert folder.

## Discussion

The enrollSimpleUserCert sample:

1.  Processes the command line arguments. The command line should contain the name of the template, the subject name, and the key length.
2.  Creates an [**IX509Enrollment**](ix509enrollment.md) object and initializes it by using the template.
3.  Retrieves the inner certificate request object from the enrollment object and queries it for the [**IX509CertificateRequestPkcs10**](ix509certificaterequestpkcs10.md) object. The innermost request is always a PKCS \#10 request.
4.  Retrieves the [**IX509PrivateKey**](ix509privatekey.md) object from the PKCS \#10 request and sets the key length specified on the command line.
5.  Creates an [**IX500DistinguishedName**](ix500distinguishedname.md) object, uses it to encode the X.500 subject name, and adds the name to the PKCS \#10 request.
6.  Attempts to enroll the end user with the CA and monitors the progress of the enrollment process. The checkEnrollStatus function is defined in enrollCommon.cpp.

## Related topics

<dl> <dt>

[PKCS \#10 Request](pkcs--10-request.md)
</dt> <dt>

[Using the Included Samples](using-the-included-samples.md)
</dt> </dl>

 

 


