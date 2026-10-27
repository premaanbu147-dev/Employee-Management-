EMPLOYEE MANAGEMENT WITH AUDIT LOGGING — ECLIPSE SETUP

Requirements:
- JDK 21
- Eclipse IDE for Enterprise Java and Web Developers (recommended)
- Internet access for Maven dependencies

IMPORT INTO ECLIPSE:
1. Extract the ZIP file.
2. Open Eclipse.
3. Select File > Import > Maven > Existing Maven Projects > Next.
4. Browse to the extracted employee-audit folder.
5. Ensure pom.xml is selected, then click Finish.
6. Right-click the project > Maven > Update Project... > OK. Wait for downloads.
7. Confirm the project uses JDK 21: Project > Properties > Java Build Path > Libraries.
8. Run tests: right-click EmployeeServiceTest.java > Run As > JUnit Test.
9. Start app: open EmployeeAuditApplication.java > Run As > Java Application.
10. Open http://localhost:8080/ in a browser.

If Eclipse doesn't recognise Maven or Java, configure a JDK 21 under Window > Preferences > Java > Installed JREs.
The employee list is stored in memory and resets when the app stops.
