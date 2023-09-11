# Initial Report for Internews

**Project:** OnionShare Release Process Improvement<br>
**Reporting Period:** Q1 2023

## Executive Summary
    
In this first quarter of activity, the OnionShare team has made significant progress in improving and streamlining the release process for its software across multiple platforms. With the challenges and complexities inherent to OnionShare’s diverse architecture and the extensive work done by Micah, our dev lead, we have outlined our achievements, new partnerships, and the methodologies we have employed to reach our goals for this period.

## Key Achievements (some items in progress)

**1. Transition to 64-bit for Windows**
  - All previous Windows versions of OnionShare were 32-bit. The recent upgrade to PySide6 necessitated a move to abandon support for 32-bit Windows, resulting in the forthcoming 2.6.1 release being 64-bit.
    
**2. Support for Apple Silicon Macs**
  - We have successfully integrated support for both Intel and Apple Silicon in our macOS version. This strategic move enhances the usability and accessibility of our software for an increasingly diverse hardware market.

**3. Snapcraft and Flatpak for Linux**
  - Instead of trying to cater to a multitude of Linux distributions, we've chosen to focus our efforts on releases for Snapcraft and Flatpak. This strategy ensures broad compatibility without the need to individually cater to each distro variant.

**4. Code Signing Overhaul**
  - Switched our Windows code signing certificate provider from the Polish CA Certum to HARICA, a Certificate Authority managed by Greek universities.
  - Maintained our Apple Developer key for the macOS application bundle.
  - The code signing keys are now safeguarded on physical USB smart cards, ensuring heightened security.

**5. Collaboration with Science & Design**
  - Our partnership with the newly-formed nonprofit, Science & Design, has opened new avenues for financial support. Science & Design, spearheaded by Glenn Sorrentino, has become the fiscal sponsor for OnionShare, further ensuring the continuity and vibrancy of the project.

**6. Software Dependency Management**
  - Successful migration from PySide2 to PySide6.
  - Efficient management and inclusion of various software dependencies like PySide6, tor, libevent, and several others.

**7. Automated Release Workflow**
  - We've initiated the use of a GitHub Actions workflow to automate the building of binaries across various platforms. This initiative drastically reduces manual intervention and streamlines the release process.

**8. Localization**
  - Maintaining OnionShare’s commitment to accessibility, we ensure that all translations are incorporated during every release. This quarter saw comprehensive work done in updating and verifying language support.

**9. Documentation Updates**
  - Our internal release procedure, detailed in the RELEASE.md file in our git repository, has been continuously updated to reflect the changes and improvements we implement.

## Challenges and Solutions

- The task of supporting various platforms and versions, particularly with respect to the differing dependencies each requires, has been a persistent challenge. This quarter, our solution has been to focus on broad compatibility platforms like Snapcraft and Flatpak for Linux.
- Code signing presented hurdles, especially considering the transition from Certum to HARICA. Yet, our team efficiently managed this transition, ensuring continued trust and security for our user base.

## Project Management and Strategy

A significant area of focus this quarter has been the strengthening of our project management protocols. It's essential that our strategies and frameworks are both robust and adaptable, given the technical complexity of our project and the diversity of platforms we cater to.

**1. Strategic Planning**
  - Alignment across team members of high-level goals and milestoes for release optmization and cross-training.
  - Create outline for rapid cycles of improving and releasing OnionShare’s desktop and web properties, iterating on our process and optimizing for efficient packaging and delivery.

**2. Framework for Execution**
  - Our team adopted a framework promoting operating system coverage, staff redundancy, and processes of optimizing our code releases. 
  - This method ensured all members were aware of their responsibilities and could swiftly adapt to changes.

**3. Hardware Acquisition**
  - We've arrived at the devices required for complete coverage for code signing. 
  - HARICA signing keys have begun to get distributed to team members.

**4. Collaborative Tool Integration**
  - Keybase has been utilized for team communication and sharing updates.
  - Github used for collecting and communicating foundational project information, relevant grant documentation, and code repositories.

## Conclusion and Future Directions 

This initial phase marks a period of growth and innovation for the OnionShare team. Our dedication to streamlining the release process, ensuring broad compatibility, and enhancing user trust is reflected in the steps we've taken already. Looking forward, we anticipate the full adoption of the aforementioned improvements, while also continuing to explore ways to automate, innovate, and expand.

We express our gratitude to Internews for the grant provided and remain committed to upholding the highest standards in the subsequent quarters.
