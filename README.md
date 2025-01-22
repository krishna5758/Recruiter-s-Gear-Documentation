# Recruiter-s-Gear-Documentation
<h2> :wrench: Project Structure : </h2>
ATS_Backend <br>
│<br>
├── ATS_Project_01<br>
│ &nbsp&nbsp&nbsp  ├── src<br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  ├── main<br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  ├── java<br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  │&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp └── 🔽 ATS_01.ATS_Project_01<br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  │&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp     &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  📦 config <br> 
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  │&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp           &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp    📄 Configuration   <br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  │&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp      &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp 📦 controller <br> 
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  │&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp           &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp    📄 ApplicantController   <br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  │&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp       &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp 📦 dto  <br> 
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  │&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp            &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp    📄 ApplicantDto   <br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  │&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp      &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp 📦 exception <br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  │&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp             &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp    📄 ApplicantExceptionHandler   <br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  │&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp      &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp 📦 model <br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  │&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp              &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp    📄 Applicant   <br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  │&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp      &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp 📦 repository <br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  │&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp               &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp    📄 ApplicantRepository   <br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  │&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp      &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp 📦 security <br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  │&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp                &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp    📄 Security   <br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  │&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp      &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp 📦 SocketEmitEvents <br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  │&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp                &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp    📄 Socket   <br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  │&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp      &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp 📦 Util <br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  │&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp                 &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp    📄 ApplicantUtil   <br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  │&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp      &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp 📦 mailSender  <br>  
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  │&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp                  &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp    📄 ApplicantMailSender   <br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  │&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp      &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp 📦 helper  <br>  
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  │&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp                    &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp    📄 ApplicantHelper   <br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  │&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp       &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp 📦 service  <br> 
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  │&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp                    &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp    📄 ApplicantService   <br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  │&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp       &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp 🚀 AtsProject01Application  <br> 
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  └── 🔽 :file_folder: resources<br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp      &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp 🔽 :file_folder: META-INF   <br> 
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp            &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp 📄 MANIFEST.FM <br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp     &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp ⚙️ application.properties<br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  └── static       <br>        
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  └── 🔽 :file_folder: test<br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp      └──  &nbsp&nbsp&nbsp 🔽 :file_folder: java<br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp          └──  &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  🔽 :file_folder: ATS_01.ATS_Project_01<br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp              └── AtsProject01ApplicationTests.java <br>
│ &nbsp&nbsp&nbsp  ├──🔽 target     <br> 
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  📄 mvnw       <br>                       
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp 📄 mvnw.cmd     <br>                     
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  📄 .gitignore    <br>                    
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  📄 pom.xml         <br> 
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  ├── 🔽 :file_folder: Out <br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp &nbsp&nbsp&nbsp &nbsp&nbsp&nbsp  ├── 🔽 :file_folder: artifacts <br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │  &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp ├── :file_folder: ATS_Project_01_jar   <br>     
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  │  &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp └──  &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp 📄 ATS_Project_01.jar   <br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  └── other_compiled_files <br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp<br>
│ &nbsp&nbsp&nbsp  ├── External Libraries <br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp  &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp 📄 <17> C:\Programs Files\Java\jdk-17 <br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp<br>
│ &nbsp&nbsp&nbsp  │ &nbsp&nbsp&nbsp<br>                
│<br>
├── 🔽 :file_folder: .idea    <br>                             
│ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  📜 misc.xml<br>
│ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  📄.gitignore <br>
│ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  📄 ATS_Backend.iml <br>
│ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  📜 compiler.xml<br>
│ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  📜 encodings.xml<br>
│ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  📜 jarRepositories.xml<br>
│ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  📜 material_theme_project_new.xml<br>
│ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  📜 misc.xml<br>
│ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  📜 modules.xml<br>
│ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  📜 workspace.xml<br>
│ &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  📜 uiDesigner.xml <br>
│<br>
└── README.md    <br>  

<h2>Demo With Add Employee: </h2>
<h3>Service Layer: </h3>

```
package _7.project1.Service;

import _7.project1.Entity.Employee;
import _7.project1.Repository.CallingTrackerRepository;
import _7.project1.Repository.EmployeeRepository;
import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.stereotype.Service;

import java.util.Optional;

@Service
public class EmployeeService {

    @Autowired
    private EmployeeRepository employeeRepository;

    @Autowired
    private CallingTrackerRepository callingTrackerRepository;


    public Employee addEmployee(Employee employee){
        Optional<Employee> existingEmployee = employeeRepository.findByUserName(employee.getUserName());
        if (existingEmployee.isPresent()){

            Employee updatedEmployee = existingEmployee.get();
            updatedEmployee.setEmployeeName(employee.getEmployeeName());
            updatedEmployee.setUserName(employee.getUserName());
            updatedEmployee.setDateOfBirth(employee.getDateOfBirth());
            updatedEmployee.setDateOfJoining(employee.getDateOfJoining());
            updatedEmployee.setDesignation(employee.getDesignation());
            updatedEmployee.setDepartment(employee.getDepartment());
            updatedEmployee.setOfficialMail(employee.getOfficialMail());
            updatedEmployee.setEmployeeEmail(employee.getEmployeeEmail());
            updatedEmployee.setOfficialContactNumber(employee.getOfficialContactNumber());
            updatedEmployee.setAlternateContactNo(employee.getAlternateContactNo());
            updatedEmployee.setGender(employee.getGender());
            updatedEmployee.setCompanyMobileNumber(employee.getCompanyMobileNumber());
            updatedEmployee.setWhatsAppNumber(employee.getWhatsAppNumber());
            updatedEmployee.setEmergencyContactNumber(employee.getEmergencyContactNumber());
            updatedEmployee.setEmergencyPersonRelation(employee.getEmergencyPersonRelation());
            updatedEmployee.setEmployeePresentAddress(employee.getEmployeePresentAddress());
            updatedEmployee.setEmployeeExperience(employee.getEmployeeExperience());
            updatedEmployee.setPerks(employee.getPerks());
            updatedEmployee.setMaritalStatus(employee.getMaritalStatus());
            updatedEmployee.setAnniversaryDate(employee.getAnniversaryDate());
            updatedEmployee.setTshirtSize(employee.getTshirtSize());
            updatedEmployee.setLastCompany(employee.getLastCompany());
            updatedEmployee.setWorkLocation(employee.getWorkLocation());
            updatedEmployee.setEntrySource(employee.getEntrySource());
            updatedEmployee.setEmployeeStatus(employee.getEmployeeStatus());
            updatedEmployee.setLastWorkingDate(employee.getLastWorkingDate());
            updatedEmployee.setReasonForLeaving(employee.getReasonForLeaving());
            updatedEmployee.setInductionYesOrNo(employee.getInductionYesOrNo());
            updatedEmployee.setInductionComment(employee.getInductionComment());
            updatedEmployee.setTrainingSource(employee.getTrainingSource());
            updatedEmployee.setTrainingCompletedYesOrNo(employee.getTrainingCompletedYesOrNo());
            updatedEmployee.setTrainingTakenCount(employee.getTrainingTakenCount());
            updatedEmployee.setRoundsOfInterview(employee.getRoundsOfInterview());
            updatedEmployee.setInterviewTakenPerson(employee.getInterviewTakenPerson());
            updatedEmployee.setWarningComments(employee.getWarningComments());
            updatedEmployee.setPerformanceIndicator(employee.getPerformanceIndicator());
            updatedEmployee.setTeamLeaderMsg(employee.getTeamLeaderMsg());
            updatedEmployee.setEditDeleteAuthority(employee.getEditDeleteAuthority());
            updatedEmployee.setLinkedInURl(employee.getLinkedInURl());
            updatedEmployee.setFaceBookURL(employee.getFaceBookURL());
            updatedEmployee.setTwitterURl(employee.getTwitterURl());
            updatedEmployee.setEmployeeAddress(employee.getEmployeeAddress());
            updatedEmployee.setBloodGroup(employee.getBloodGroup());
            updatedEmployee.setAadhaarNo(employee.getAadhaarNo());
            updatedEmployee.setPanNo(employee.getPanNo());
            updatedEmployee.setEducationalQualification(employee.getEducationalQualification());
            updatedEmployee.setOfferedSalary(employee.getOfferedSalary());
            updatedEmployee.setJobRole(employee.getJobRole());
            updatedEmployee.setProfessionalPtNo(employee.getProfessionalPtNo());
            updatedEmployee.setEsIcNo(employee.getEsIcNo());
            updatedEmployee.setPfNo(employee.getPfNo());
            updatedEmployee.setInsuranceNumber(employee.getInsuranceNumber());
            updatedEmployee.setReportingMangerName(employee.getReportingMangerName());
            updatedEmployee.setReportingMangerDesignation(employee.getReportingMangerDesignation());
            updatedEmployee.setEmployeePassword(employee.getEmployeePassword());
            updatedEmployee.setConfirmPassword(employee.getConfirmPassword());
            updatedEmployee.setProfileImage(employee.getProfileImage());
            updatedEmployee.setDocument(employee.getDocument());
            updatedEmployee.setResumeFile(employee.getResumeFile());
            updatedEmployee.setOldTeamLeaderId(employee.getOldTeamLeaderId());
            updatedEmployee.setLoginStatus(employee.getLoginStatus());

            return employeeRepository.save(updatedEmployee);
        } else {
            return employeeRepository.save(employee);
        }
    }

    public Optional<Employee> getEmployeeByUserName(String username){
        return employeeRepository.findByUserName(username);
    }
}```

```
<h3> Controller Layer: </h3>

```
package _7.project1.Controller;

import _7.project1.Dto.CallingTrackerLineUpDto;
import _7.project1.Entity.Employee;
import _7.project1.Service.CallingTrackerService;
import _7.project1.Service.EmployeeService;
import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.http.HttpStatus;
import org.springframework.http.ResponseEntity;
import org.springframework.web.bind.annotation.*;
import java.time.LocalDate;

@RestController
@RequestMapping("/api/employee")
public class EmployeeController {

    @Autowired
    private EmployeeService employeeService;

    @Autowired
    private CallingTrackerService callingTrackerService;

    @PostMapping("/add")
    public ResponseEntity<Employee> addEmployee( @RequestBody Employee employee){
        try{
            return new ResponseEntity<>(employeeService.addEmployee(employee), HttpStatus.OK);

        }catch (RuntimeException e){
            return new ResponseEntity<>(null, HttpStatus.BAD_REQUEST);
        }
    }
```
<h3>Entity: </h3>

```
package _7.project1.Entity;

import jakarta.persistence.*;
import lombok.AllArgsConstructor;
import lombok.NoArgsConstructor;

@Entity
@NoArgsConstructor
@AllArgsConstructor
@Table(name = "employee",uniqueConstraints = {@UniqueConstraint(columnNames = "user_name")})
public class Employee {

    @Id
    @GeneratedValue(strategy = GenerationType.SEQUENCE,generator = "employee_seq_generator")
    @SequenceGenerator(name = "employee_seq_generator",sequenceName = "employee_seq",
                 allocationSize = 1)
    @Column(name ="emp_id")
    private Long employee_Id;

    @Column(name = "employee_name")
    private String employeeName;

    @Column(name = "user_name",unique = true, nullable = false)
    private String userName;

    @Column(name = "date_of_joining")
    private String dateOfJoining;

    @Column(name = "designation")
    private String designation;

    @Column(name = "department")
    private String department;

    @Column(name = "official_mail")
    private String officialMail;

    @Column(name = "employee_email")
    private String employeeEmail;

    @Column(name = "official_contact_no")
    private long officialContactNumber;

    @Column(name = "alternate_contact_no")
    private long alternateContactNo;

    @Column(name = "date_of_birth")
    private String dateOfBirth;

    @Column(name = "gender")
    private String gender;

    @Column(name = "company_mobile_number")
    private long companyMobileNumber;

    @Column(name = "whats_App_number")
    private long whatsAppNumber;

    @Column(name = "emergency_contact_number")
    private String emergencyContactNumber;

    @Column(name = "emergency_person_relation")
    private String emergencyPersonRelation;

    @Column(name = "employee_present_address")
    private String employeePresentAddress;

    @Column(name = "employee_experience")
    private String employeeExperience;

    @Column(name = "perks")
    private String perks;

    @Column(name = "marital_status")
    private String maritalStatus;

    @Column(name = "anniversary_date")
    private String anniversaryDate;

    @Column(name = "t_shirt_size")
    private String tshirtSize;

    @Column(name = "last_company")
    private String lastCompany;

    @Column(name = "work_location")
    private String workLocation;

    @Column(name = "entry_source")
    private String entrySource;

    @Column(name = "employee_status")
    private String employeeStatus;

    @Column(name = "last_working_date")
    private String lastWorkingDate;

    @Column(name = "reason_for_leaving")
    private String reasonForLeaving;

    @Column(name = "induction_yes_or_no")
    private String inductionYesOrNo;

    @Column(name = "induction_comment")
    private String inductionComment;

    @Column(name = "training_source")
    private String trainingSource;

    @Column(name = "training_completed_yes_or_no")
    private String trainingCompletedYesOrNo;

    @Column(name = "training_taken_count")
    private int trainingTakenCount;

    @Column(name = "rounds_of_interview")
    private String roundsOfInterview;

    @Column(name = "interview_taken_person")
    private String interviewTakenPerson;

    @Column(name = "warning_comments")
    private String warningComments;

    @Column(name = "performance_indicator")
    private String performanceIndicator;

    @Column(name = "team_leader_msg")
    private String teamLeaderMsg;

    @Column(name = "edit_delete_authority")
    private String editDeleteAuthority;

    @Column(name = "linked_inurl")
    private String linkedInURl;

    @Column(name = "face_bookurl")
    private String faceBookURL;

    @Column(name = "twitterurl")
    private String twitterURl;

    @Column(name = "employee_address")
    private String employeeAddress;

    @Column(name = "blood_group")
    private String bloodGroup;

    @Column(name = "aadhaar_no")
    private long aadhaarNo;

    @Column(name = "pan_no")
    private String panNo;

    @Column(name = "educational_qualification")
    private String educationalQualification;

    @Column(name = "offered_salary")
    private double offeredSalary;

    @Column(name = "job_role")
    private String jobRole;

    @Column(name = "professional_pt_no")
    private long professionalPtNo;

    @Column(name = "es_ic_no")
    private long esIcNo;

    @Column(name = "pf_no")
    private long pfNo;

    private long insuranceNumber;
    private String reportingMangerName;
    private String reportingMangerDesignation;

    @Column(name = "employee_password")
    private String employeePassword;

    @Column(name = "confirm_password")
    private String confirmPassword;

    @Lob
    @Column(columnDefinition = "LONGBLOB",name = "profile_image")
    private byte[] profileImage;

    @Lob
    @Column(columnDefinition = "LONGBLOB",name = "document")
    private byte[] document;

    @Lob
    @Column(columnDefinition = "LONGBLOB",name = "resume_file")
    private byte[] resumeFile;

    private int oldTeamLeaderId;

    @Column(name="login_status")
    private String loginStatus;

    public Long getEmployee_Id() {
        return employee_Id;
    }

    public void setEmployee_Id(Long employee_Id) {
        this.employee_Id = employee_Id;
    }

    public String getEmployeeName() {
        return employeeName;
    }

    public void setEmployeeName(String employeeName) {
        this.employeeName = employeeName;
    }

    public String getUserName() {
        return userName;
    }

    public void setUserName(String userName) {
        this.userName = userName;
    }

    public String getDateOfJoining() {
        return dateOfJoining;
    }

    public void setDateOfJoining(String dateOfJoining) {
        this.dateOfJoining = dateOfJoining;
    }

    public String getDesignation() {
        return designation;
    }

    public void setDesignation(String designation) {
        this.designation = designation;
    }

    public String getDepartment() {
        return department;
    }

    public void setDepartment(String department) {
        this.department = department;
    }

    public String getOfficialMail() {
        return officialMail;
    }

    public void setOfficialMail(String officialMail) {
        this.officialMail = officialMail;
    }

    public String getEmployeeEmail() {
        return employeeEmail;
    }

    public void setEmployeeEmail(String employeeEmail) {
        this.employeeEmail = employeeEmail;
    }

    public long getOfficialContactNumber() {
        return officialContactNumber;
    }

    public void setOfficialContactNumber(long officialContactNumber) {
        this.officialContactNumber = officialContactNumber;
    }

    public long getAlternateContactNo() {
        return alternateContactNo;
    }

    public void setAlternateContactNo(long alternateContactNo) {
        this.alternateContactNo = alternateContactNo;
    }

    public String getDateOfBirth() {
        return dateOfBirth;
    }

    public void setDateOfBirth(String dateOfBirth) {
        this.dateOfBirth = dateOfBirth;
    }

    public String getGender() {
        return gender;
    }

    public void setGender(String gender) {
        this.gender = gender;
    }

    public long getCompanyMobileNumber() {
        return companyMobileNumber;
    }

    public void setCompanyMobileNumber(long companyMobileNumber) {
        this.companyMobileNumber = companyMobileNumber;
    }

    public long getWhatsAppNumber() {
        return whatsAppNumber;
    }

    public void setWhatsAppNumber(long whatsAppNumber) {
        this.whatsAppNumber = whatsAppNumber;
    }

    public String getEmergencyContactNumber() {
        return emergencyContactNumber;
    }

    public void setEmergencyContactNumber(String emergencyContactNumber) {
        this.emergencyContactNumber = emergencyContactNumber;
    }

    public String getEmergencyPersonRelation() {
        return emergencyPersonRelation;
    }

    public void setEmergencyPersonRelation(String emergencyPersonRelation) {
        this.emergencyPersonRelation = emergencyPersonRelation;
    }

    public String getEmployeePresentAddress() {
        return employeePresentAddress;
    }

    public void setEmployeePresentAddress(String employeePresentAddress) {
        this.employeePresentAddress = employeePresentAddress;
    }

    public String getEmployeeExperience() {
        return employeeExperience;
    }

    public void setEmployeeExperience(String employeeExperience) {
        this.employeeExperience = employeeExperience;
    }

    public String getPerks() {
        return perks;
    }

    public void setPerks(String perks) {
        this.perks = perks;
    }

    public String getMaritalStatus() {
        return maritalStatus;
    }

    public void setMaritalStatus(String maritalStatus) {
        this.maritalStatus = maritalStatus;
    }

    public String getAnniversaryDate() {
        return anniversaryDate;
    }

    public void setAnniversaryDate(String anniversaryDate) {
        this.anniversaryDate = anniversaryDate;
    }

    public String getTshirtSize() {
        return tshirtSize;
    }

    public void setTshirtSize(String tshirtSize) {
        this.tshirtSize = tshirtSize;
    }

    public String getLastCompany() {
        return lastCompany;
    }

    public void setLastCompany(String lastCompany) {
        this.lastCompany = lastCompany;
    }

    public String getWorkLocation() {
        return workLocation;
    }

    public void setWorkLocation(String workLocation) {
        this.workLocation = workLocation;
    }

    public String getEntrySource() {
        return entrySource;
    }

    public void setEntrySource(String entrySource) {
        this.entrySource = entrySource;
    }

    public String getEmployeeStatus() {
        return employeeStatus;
    }

    public void setEmployeeStatus(String employeeStatus) {
        this.employeeStatus = employeeStatus;
    }

    public String getLastWorkingDate() {
        return lastWorkingDate;
    }

    public void setLastWorkingDate(String lastWorkingDate) {
        this.lastWorkingDate = lastWorkingDate;
    }

    public String getReasonForLeaving() {
        return reasonForLeaving;
    }

    public void setReasonForLeaving(String reasonForLeaving) {
        this.reasonForLeaving = reasonForLeaving;
    }

    public String getInductionYesOrNo() {
        return inductionYesOrNo;
    }

    public void setInductionYesOrNo(String inductionYesOrNo) {
        this.inductionYesOrNo = inductionYesOrNo;
    }

    public String getInductionComment() {
        return inductionComment;
    }

    public void setInductionComment(String inductionComment) {
        this.inductionComment = inductionComment;
    }

    public String getTrainingSource() {
        return trainingSource;
    }

    public void setTrainingSource(String trainingSource) {
        this.trainingSource = trainingSource;
    }

    public String getTrainingCompletedYesOrNo() {
        return trainingCompletedYesOrNo;
    }

    public void setTrainingCompletedYesOrNo(String trainingCompletedYesOrNo) {
        this.trainingCompletedYesOrNo = trainingCompletedYesOrNo;
    }

    public int getTrainingTakenCount() {
        return trainingTakenCount;
    }

    public void setTrainingTakenCount(int trainingTakenCount) {
        this.trainingTakenCount = trainingTakenCount;
    }

    public String getRoundsOfInterview() {
        return roundsOfInterview;
    }

    public void setRoundsOfInterview(String roundsOfInterview) {
        this.roundsOfInterview = roundsOfInterview;
    }

    public String getInterviewTakenPerson() {
        return interviewTakenPerson;
    }

    public void setInterviewTakenPerson(String interviewTakenPerson) {
        this.interviewTakenPerson = interviewTakenPerson;
    }

    public String getWarningComments() {
        return warningComments;
    }

    public void setWarningComments(String warningComments) {
        this.warningComments = warningComments;
    }

    public String getPerformanceIndicator() {
        return performanceIndicator;
    }

    public void setPerformanceIndicator(String performanceIndicator) {
        this.performanceIndicator = performanceIndicator;
    }

    public String getTeamLeaderMsg() {
        return teamLeaderMsg;
    }

    public void setTeamLeaderMsg(String teamLeaderMsg) {
        this.teamLeaderMsg = teamLeaderMsg;
    }

    public String getEditDeleteAuthority() {
        return editDeleteAuthority;
    }

    public void setEditDeleteAuthority(String editDeleteAuthority) {
        this.editDeleteAuthority = editDeleteAuthority;
    }

    public String getLinkedInURl() {
        return linkedInURl;
    }

    public void setLinkedInURl(String linkedInURl) {
        this.linkedInURl = linkedInURl;
    }

    public String getFaceBookURL() {
        return faceBookURL;
    }

    public void setFaceBookURL(String faceBookURL) {
        this.faceBookURL = faceBookURL;
    }

    public String getTwitterURl() {
        return twitterURl;
    }

    public void setTwitterURl(String twitterURl) {
        this.twitterURl = twitterURl;
    }

    public String getEmployeeAddress() {
        return employeeAddress;
    }

    public void setEmployeeAddress(String employeeAddress) {
        this.employeeAddress = employeeAddress;
    }

    public String getBloodGroup() {
        return bloodGroup;
    }

    public void setBloodGroup(String bloodGroup) {
        this.bloodGroup = bloodGroup;
    }

    public long getAadhaarNo() {
        return aadhaarNo;
    }

    public void setAadhaarNo(long aadhaarNo) {
        this.aadhaarNo = aadhaarNo;
    }

    public String getPanNo() {
        return panNo;
    }

    public void setPanNo(String panNo) {
        this.panNo = panNo;
    }

    public String getEducationalQualification() {
        return educationalQualification;
    }

    public void setEducationalQualification(String educationalQualification) {
        this.educationalQualification = educationalQualification;
    }

    public double getOfferedSalary() {
        return offeredSalary;
    }

    public void setOfferedSalary(double offeredSalary) {
        this.offeredSalary = offeredSalary;
    }

    public String getJobRole() {
        return jobRole;
    }

    public void setJobRole(String jobRole) {
        this.jobRole = jobRole;
    }

    public long getProfessionalPtNo() {
        return professionalPtNo;
    }

    public void setProfessionalPtNo(long professionalPtNo) {
        this.professionalPtNo = professionalPtNo;
    }

    public long getEsIcNo() {
        return esIcNo;
    }

    public void setEsIcNo(long esIcNo) {
        this.esIcNo = esIcNo;
    }

    public long getPfNo() {
        return pfNo;
    }

    public void setPfNo(long pfNo) {
        this.pfNo = pfNo;
    }

    public long getInsuranceNumber() {
        return insuranceNumber;
    }

    public void setInsuranceNumber(long insuranceNumber) {
        this.insuranceNumber = insuranceNumber;
    }

    public String getReportingMangerName() {
        return reportingMangerName;
    }

    public void setReportingMangerName(String reportingMangerName) {
        this.reportingMangerName = reportingMangerName;
    }

    public String getReportingMangerDesignation() {
        return reportingMangerDesignation;
    }

    public void setReportingMangerDesignation(String reportingMangerDesignation) {
        this.reportingMangerDesignation = reportingMangerDesignation;
    }

    public String getEmployeePassword() {
        return employeePassword;
    }

    public void setEmployeePassword(String employeePassword) {
        this.employeePassword = employeePassword;
    }

    public String getConfirmPassword() {
        return confirmPassword;
    }

    public void setConfirmPassword(String confirmPassword) {
        this.confirmPassword = confirmPassword;
    }

    public byte[] getProfileImage() {
        return profileImage;
    }

    public void setProfileImage(byte[] profileImage) {
        this.profileImage = profileImage;
    }

    public byte[] getDocument() {
        return document;
    }

    public void setDocument(byte[] document) {
        this.document = document;
    }

    public byte[] getResumeFile() {
        return resumeFile;
    }

    public void setResumeFile(byte[] resumeFile) {
        this.resumeFile = resumeFile;
    }

    public int getOldTeamLeaderId() {
        return oldTeamLeaderId;
    }

    public void setOldTeamLeaderId(int oldTeamLeaderId) {
        this.oldTeamLeaderId = oldTeamLeaderId;
    }

    public String getLoginStatus() {
        return loginStatus;
    }

    public void setLoginStatus(String loginStatus) {
        this.loginStatus = loginStatus;
    }
}
```
<h3>Repository Layer: </h3>

```
package _7.project1.Repository;

import _7.project1.Entity.Employee;
import org.springframework.data.jpa.repository.JpaRepository;
import org.springframework.stereotype.Repository;
import java.util.Optional;

@Repository
public interface EmployeeRepository extends JpaRepository<Employee, Long> {
    Optional<Employee> findByUserName(String username);
    Optional<Employee> findById(Long id);
}
```
<h3>Application.properties: </h3>

```
spring.application.name=157-project1
server.port=3000
spring.datasource.url= jdbc:MySql://localhost:3306/157task
spring.datasource.username=root
spring.datasource.password=8446394639
#spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL8Dialect
spring.servlet.multipart.enabled=true
spring.servlet.multipart.max-file-size=10MB
spring.servlet.multipart.max-request-size=10MB

```










