
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
<p>The Service Layer in Spring Boot is a key part of the application architecture, typically responsible for handling business logic.</p>
<p> * It acts as a middle layer between the Controller and the Repository.</p>
<p> * Contains business logic and rules, ensuring separation of concerns.</p>
<p> * Helps keep controllers slim and focused on handling HTTP requests and responses.</p>

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
<p>The Controller in Spring Boot is part of the presentation layer. Its primary role is to handle HTTP requests and map them to specific methods in your application. It interacts with the Service Layer to process data and return appropriate responses.
<p>Maps HTTP requests (GET, POST, PUT, DELETE, etc.) to specific methods using annotations like @GetMapping, @PostMapping, etc.</p>

</p>

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
<p>The Entity in Spring Boot is part of the data access layer. It represents a table in a database, with each instance of the entity corresponding to a row in the table. Entities are typically annotated with JPA (Java Persistence API) annotations to map Java classes to database tables.</p>
<p>@Entity: Marks a class as a JPA entity (required for ORM mapping).</p>
<p>@Table: Specifies the table name (optional, defaults to the class name).</p>
<p>@Id: Marks the primary key field.</p>
<p>@GeneratedValue: Specifies how the primary key should be generated (e.g., AUTO, SEQUENCE, IDENTITY).</p>
<p>@Column: Customizes the column mapping (e.g., name, nullable, length).</p>
<p>@ManyToOne, @OneToMany, @ManyToMany, @OneToOne: Define relationships between entities.</p>
<p>@Embeddable: Used for composite key mapping or embedded types.</p>


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
<p>The Repository in Spring Boot is part of the data access layer and is responsible for directly interacting with the database. It provides methods to perform CRUD operations (Create, Read, Update, Delete) on entities, typically using Spring Data JPA.</p>
<p>Database Operations</p>
<p>Abstraction</p>
<p>Custom Queries</p>

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
<p>The application.properties file in Spring Boot is used to configure application-level settings and behaviors. It acts as a centralized configuration file for various components like the database, server, logging, etc.</p>
<h4>Purpose Of Using Application.properties: </h4>
<p>Database Configuration</p>
<p>Server Configuration</p>
<p>Spring Profiles</p>
<p>Custom Application Settings</p>

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
<h3> Demostration: </h3>

![Screenshot 2025-01-23 101118](https://github.com/user-attachments/assets/17a0d5ef-63d6-4305-a393-fb0e1caad3de)

<h3> 🔗 Dependencies Used In Project: </h3>
<p> 1) spring-boot-starter-data-jpa</p>

```
<dependency>
	<groupId>org.springframework.boot</groupId>
	<artifactId>spring-boot-starter-data-jpa</artifactId>
</dependency>
```
<p> <dependency> with the group ID org.springframework.boot and artifact ID spring-boot-starter-data-jpa is a Spring Boot starter that  simplifies the integration of Spring Data JPA into your application. It provides all the necessary libraries and tools required for working  with relational databases using JPA (Java Persistence API) and Hibernate.</p>
<h4>Key Features:</h4>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • JPA Integration: Enables the use of JPA for object-relational mapping (ORM) to map Java objects to database tables.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Hibernate Support: Includes Hibernate as the default JPA implementation, providing advanced ORM capabilities.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Repository Support: Provides repository interfaces (like JpaRepository) to perform CRUD operations and custom queries without writing boilerplate code.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Transaction Management: Simplifies declarative transaction management using @Transactional.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Database Schema Generation: Automatically generates or updates database schemas based on your JPA entity mappings.</p>

<p>2) spring-boot-starter-web</p>

```
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-web</artifactId>
</dependency>
```
<p>This starter is used to create web applications, including RESTful web services, in Spring Boot. It comes with pre-configured settings for Spring MVC, embedded servers like Tomcat (default), Jackson for JSON binding, and more.</p>
<h4>Key Features:</h4>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Spring MVC: Supports building web applications using the Model-View-Controller architecture.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Embedded Tomcat: Includes the Tomcat server by default (you can also choose other embedded servers like Jetty or Undertow).</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Jackson: Automatically includes the Jackson library to handle JSON data binding (for REST APIs).</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Spring WebSocket: Provides support for WebSocket communication.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Common Usage: This dependency is typically used in web applications or microservices that need to <br> &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp expose REST APIs  or serve web pages.</p>

<p>3) spring-boot-devtools </p>

```
<dependency>
	<groupId>org.springframework.boot</groupId>
		<artifactId>spring-boot-devtools</artifactId>
		<scope>runtime</scope>
	<optional>true</optional>
</dependency>
```
<p>This dependency is used to improve the development workflow by providing features such as automatic restarts, live reload, and remote debugging for Spring Boot applications. It’s meant for use during the development phase only.</p>
<h4>Key Features:</h4>

<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Automatic Restart: When you make changes to your application, it automatically restarts the application without needing a<br>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp manual restart, which speeds up the development process.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Live Reload: Integrates with tools like LiveReload to automatically refresh the browser when the code is modified, improving the user<br>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp experience while testing.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Configuration for Development Only: It is typically included with the runtime scope to ensure it is only included in the development<br>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp environment, not in production.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Common Usage: This dependency is added during the development phase to make the application development faster and easier. It is<br>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp not meant to be included in production.</p>

<p>4) mysql-connector-j </p>

```
<dependency>
    <groupId>com.mysql</groupId>
    <artifactId>mysql-connector-j</artifactId>
    <scope>runtime</scope>
</dependency>
```
<p> This dependency provides the JDBC driver necessary for connecting Java applications to a MySQL database. It acts as a bridge to allow your Spring Boot (or other Java) applications to send queries to and retrieve data from MySQL databases</p>
<h4>Key Features:</h4>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • JDBC Driver: Implements the Java Database Connectivity (JDBC) API, allowing Java application.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Database Connection: Facilitates establishing a connection to the MySQL database and performing CRUD (Create, Read, Update, Delete)<br> &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp operations.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Runtime Scope: Since it’s used at runtime to interact with the database, it is declared with a <scope>runtime</scope>. This ensures the dependency is<br>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp only included during the execution of the application and not during the compilation.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Common Usage: This dependency is used when a Spring Boot application needs to interact with a MySQL database. It is included in the<br>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp pom.xml file to configure the connection between the Java application and MySQL.</p>

<p>5) lombok </p>

```
<dependency>
    <groupId>org.projectlombok</groupId>
    <artifactId>lombok</artifactId>
    <optional>true</optional>
</dependency>
```
<p>Lombok is a Java library that helps reduce boilerplate code by generating common methods like getters, setters, constructors, and more at compile-time using annotations. This simplifies your code and makes it more readable and maintainable.</p>
<h4>Key Features:</h4>

<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Automatic Getter and Setter Methods: Lombok automatically generates getters and setters for fields with annotations like @Getter and<br>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  @Setter.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • @ToString, @EqualsAndHashCode: Automatically generates toString(), equals(), and hashCode() methods.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • @AllArgsConstructor, @NoArgsConstructor, @RequiredArgsConstructor: Automatically generates constructors based on the<br>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  parameters in the class.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • @Builder: Allows you to implement the builder pattern, enabling an easy and readable way to construct objects.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Compile-Time Code Generation: Lombok generates code during compilation, so it doesn’t affect runtime performance.</p>

<p>6) pdfbox </p>

```
<dependency>
    <groupId>org.apache.pdfbox</groupId>
    <artifactId>pdfbox</artifactId>
    <version>2.0.27</version>
</dependency>
```
<p>Apache PDFBox is a Java library that provides capabilities to create, manipulate, and extract data from PDF documents. It is commonly used for tasks like reading PDF files, writing data into PDFs, extracting text, and handling other PDF-related operations.</p>

<h4>Key Features:</h4>

<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Create PDF: You can generate PDF documents programmatically, adding text, images, and other content. </p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Read PDF: PDFBox allows extracting text and other elements from existing PDF files, making it useful for parsing PDF content.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Manipulate PDFs: You can manipulate existing PDF documents, such as merging, splitting, and rotating pages.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Fill Forms: You can fill in PDF forms dynamically and even generate reports in PDF format.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Signature Support: Supports adding digital signatures to PDF files.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Common Usage: This dependency is often used in Java applications that need to generate or manipulate PDF files. It's useful in <br>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp scenarios where reports, invoices, or documents need to be created or processed in PDF format.</p>

<p>7) spring-boot-starter-test </p>

```
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-test</artifactId>
    <scope>test</scope>
</dependency>
```
<p>This dependency provides the necessary tools to perform unit tests, integration tests, and other kinds of tests within a Spring Boot application. It includes a range of popular testing libraries and utilities such as JUnit, Mockito, and Spring TestContext Framework.</p>

<h4>Key Features:</h4>

<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • JUnit: The most widely used testing framework in Java for writing and running tests. Spring Boot Starter Test includes JUnit 5 by default. </p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Mockito: A mocking framework used to create mock objects for unit testing. Mockito helps simulate behaviors of dependencies and<br>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp ensures that tests remain isolated. </p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Spring TestContext Framework: Provides support for integration testing with Spring’s TestContext framework. This allows for setting up<br>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp application contexts and running tests in a Spring-managed environment.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Spring Boot Test: Provides annotations like @SpringBootTest to set up an application context for testing, ensuring tests run in a full<br>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp Spring Boot environment. </p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Hamcrest: A library for writing declarative assertions in tests (e.g., assertThat statements).</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • JSON and XML testing: Provides support for validating JSON and XML responses in integration tests.</p>

<p>8) socket.io-client </p>

```
<dependency>
    <groupId>com.corundumstudio.socketio</groupId>
    <artifactId>netty-socketio</artifactId>
    <version>2.0.12</version>
</dependency>

```
<p>The netty-socketio library is a Java implementation of Socket.IO that uses Netty for handling network connections. It allows Java-based applications to support real-time, event-driven communication between clients and servers via WebSockets or other fallback protocols.</p>

<h4>Key Features:</h4>

<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Real-time Communication: Enables low-latency, bidirectional communication between a client and a server using WebSockets or long<br>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp polling.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Socket.IO Protocol: Implements the Socket.IO protocol, allowing Java applications to communicate with Socket.IO clients (e.g.<br>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp, JavaScript clients).</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Built on Netty: Uses Netty, a non-blocking I/O framework, to handle incoming requests, enabling scalability and efficiency in handling<br>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp many concurrent connections.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Event-driven Model: Allows the server to emit and listen for events, enabling real-time functionality like chat, notifications, and live<br>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp updates.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Compatibility with Socket.IO Clients: Supports communication with Socket.IO clients written in JavaScript, making it ideal for full-stack<br>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp real-time applications.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Live data applications: Suitable for applications that require real-time data updates, such as sports scores, financial data, and stock<br>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp prices.</p>

<p>9) spring-boot-starter-validation </p>

```
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-validation</artifactId>
</dependency>
```
<p>The <dependency> with the group ID org.springframework.boot and artifact ID spring-boot-starter-validation provides support for validating user input in Spring Boot applications. It integrates the Java Bean Validation API (JSR 380) with Spring Boot and uses Hibernate Validator as the default implementation.</p>

<h4>Key Features:</h4>

<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Input Validation: Allows you to validate user input in request payloads (e.g., @RequestBody or @ModelAttribute). </p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Built-in Annotations: Provides standard validation annotations like @NotNull, @Size, @Email, @Pattern, etc.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Custom Validation: Supports custom validation logic using custom constraint annotations.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Error Handling: Automatically generates meaningful error messages for invalid inputs, which can be customized.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Validation Groups: Supports grouping of validation rules for different scenarios.</p>

<p>10) jackson-databind </p>

```
<dependency>
    <groupId>com.fasterxml.jackson.core</groupId>
    <artifactId>jackson-databind</artifactId>
</dependency>
```
<p>The <dependency> with the group ID com.fasterxml.jackson.core and artifact ID jackson-databind is a key component of the Jackson library. Jackson is a widely used Java library for converting Java objects to JSON and vice versa. Specifically, jackson-databind is used for data binding, allowing you to map Java objects to JSON and back, supporting both serialization and deserialization.</p>

<h4>Key Features:</h4>

<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Serialization and Deserialization: Converts Java objects to JSON (serialization) and JSON to Java objects(deserialization). </p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Supports Various Data Types: Handles collections, lists, maps, and other custom types seamlessly.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Custom Serialization/Deserialization: Supports custom serializers and deserializers for complex or non-standard Java types. </p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Configuration Flexibility: Allows customization of JSON processing, including handling of null values, pretty printing, etc.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Annotation Support: Integrates with Jackson annotations like @JsonProperty, @JsonIgnore, @JsonFormat, etc., to control how Java<br>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp objects are converted to JSON.</p>

<p>11) jackson-annotations </p>

```
<dependency>
     <groupId>com.fasterxml.jackson.core</groupId>
     <artifactId>jackson-annotations</artifactId>
</dependency>
```
<p>The <dependency> with the group ID com.fasterxml.jackson.core and artifact ID jackson-annotations is part of the Jackson library. This dependency provides annotations that allow developers to customize how Java objects are serialized (converted to JSON) and deserialized (converted from JSON) using Jackson.</p>

<h4>Key Features:</h4>

<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Customization of JSON Mapping: Allows fine-grained control over how Java object fields and methods are mapped to JSON properties and vice versa. </p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Improved Serialization/Deserialization: Helps configure how specific fields are included, excluded, renamed, or formatted when converting between Java objects and JSON. </p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Reduction of Boilerplate Code:Simplifies the JSON processing by adding annotations directly to your Java classes, avoiding manual configuration in code.  </p>

<p>12) spring-boot-starter-websocket </p>

```
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-websocket</artifactId>
</dependency>
```
<p>The <dependency> with the group ID org.springframework.boot and artifact ID spring-boot-starter-websocket is used to enable WebSocket support in a Spring Boot application.</p>

<h4>Key Features:</h4>

<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Real-Time Communication: Enables continuous two-way communication between the client and the server.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Reduced Latency: Unlike HTTP, WebSocket connections remain open, removing the need for repeated requests.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Event-Driven Architecture: Suitable for event-based use cases where updates need to be pushed to the client in real-time.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Chat Applications: Sending and receiving messages instantly between clients.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Real-Time Dashboards: Live stock market data, user activity tracking, etc.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Gaming: Multiplayer games that require instant communication between players.</p>

<p>13) jakarta.validation-api </p>

```
<dependency>
    <groupId>jakarta.validation</groupId>
    <artifactId>jakarta.validation-api</artifactId>
    <version>3.0.2</version>
</dependency>
```
<p>The jakarta.validation-api is the standard for Java Bean Validation and allows you to validate the constraints on:

Class fields. 
Method parameters.
Return values.
It is often used in conjunction with Hibernate Validator, which is the reference implementation of the Jakarta Bean Validation API.</p>

<h4>Key Features:</h4>

<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Declarative Validation with Annotations: Validate fields, methods, or parameters using annotations such as @NotNull, @Size, @Min, etc. </p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Custom Constraints: Create your own validation logic with custom annotations.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Integration with Frameworks: Supported out-of-the-box in frameworks like Spring Boot, where validations are automatically triggered.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Cross-Parameter Validation: Validate parameters across method calls or fields in a class.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp •@NotNull: Ensures the value is not null. </p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp •@Size: Validates the size of a collection, array, or string.</p>

<p>14) modelmapper </p>

```
<dependency>
    <groupId>org.modelmapper</groupId>
    <artifactId>modelmapper</artifactId>
    <version>3.1.1</version>
</dependency>
```
<p>The <dependency> with the group ID org.modelmapper and artifact ID modelmapper provides a library for object mapping in Java. It simplifies the process of transferring data between objects, especially when working with layers like DTOs (Data Transfer Objects) and entities in applications.</p>

<h4>Key Features:</h4>

<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Automated Mapping: Automatically maps fields with matching names and compatible types between two objects.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Customizable Mapping: Supports defining custom mapping logic for specific scenarios.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Property Mapping: Maps fields even if their names don't match, by using configuration or explicit mapping rules.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Bidirectional Mapping: Supports mapping in both directions (e.g., Entity → DTO and DTO → Entity).</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Collections Mapping: Handles mapping between collections (e.g., List of entities to List of DTOs).</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Deep Mapping: Maps nested objects and complex structures.</p>

<p>15) commons-io </p>

```
<dependency>
    <groupId>commons-io</groupId>
    <artifactId>commons-io</artifactId>
    <version>2.11.0</version>
</dependency>
```
<p>The Apache Commons IO library is used to:

Simplify file and stream manipulation.
Perform operations like copying files, reading/writing text, monitoring directories, etc.
Handle advanced I/O tasks such as dealing with file filters, byte arrays, and file comparisons.
</p>

<h4>Key Features:</h4>

<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • File Utilities: Simplifies file operations like copying, deleting, moving, and comparing files.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Stream Utilities: Makes it easier to work with InputStream and OutputStream.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • IO Monitoring: Supports monitoring changes in directories (e.g., file creation, deletion, or modification).</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • File Filters: Provides ready-to-use filters to select files based on conditions (e.g., by extension or size).</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Filename Utilities: Handles filename manipulation like extracting extensions or normalizing paths.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Endian Support: Provides utilities to work with big-endian and little-endian data.</p> 

<p>16) netty-codec-http </p>

```
<dependency>
     <groupId>io.netty</groupId>
     <artifactId>netty-codec-http</artifactId>
     <version>4.1.107.Final</version> <!-- You can choose the appropriate version -->
</dependency>
```
<p>The <dependency> with the group ID io.netty and artifact ID netty-codec-http is part of the Netty framework, which is a popular library for building network applications in Java. Specifically, this module provides support for working with HTTP and HTTP/2 protocols.</p>

<h4>Key Features:</h4>

<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • HTTP Encoding/Decoding: Automatically encodes/decodes HTTP messages (requests and responses).</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • HTTP/2 Support: Provides tools to handle HTTP/2 frames and multiplexing.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Lightweight and Efficient: Built for performance and scalability, suitable for high-throughput applications.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Custom Protocol Handling: Allows customization of HTTP handling logic for specific use cases.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Integration with Other Netty Modules: Works seamlessly with other Netty modules like netty-handler and netty-buffer.</p>

<p>17) jakarta.mail:jakarta.mail-api </p>

```
<dependency>
     <groupId>jakarta.mail</groupId>
     <artifactId>jakarta.mail-api</artifactId>
     <version>2.1.1</version>
</dependency>
```
<p>The <dependency> with groupId as jakarta.mail and artifactId as jakarta.mail-api provides the Jakarta Mail API (previously known as JavaMail). This dependency is used for building email functionality in Java applications, such as sending and receiving emails via SMTP, POP3, or IMAP protocols.</p>

<h4>Key Features:</h4>

<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • SMTP Support: Send emails using Simple Mail Transfer Protocol (SMTP).</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • POP3/IMAP Support: Retrieve emails from mail servers.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Attachments: Add file attachments or inline images to emails.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Authentication: Supports authentication for secure email communication.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Rich Content: Send emails with HTML content and multimedia.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Custom Headers: Add custom headers to email messages.</p>

<p>18) spring-boot-starter-mail </p>

```
<dependency>
     <groupId>org.springframework.boot</groupId>
     <artifactId>spring-boot-starter-mail</artifactId>
</dependency>
```
<p>This dependency provides the necessary components to easily integrate email sending functionality into your Spring Boot applications.
It simplifies the process of configuring and sending emails using JavaMailSender interface.</p>

<h4>Key Features:</h4>

<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Easy Integration: Seamlessly integrates with Spring Boot's auto-configuration mechanism.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • JavaMailSender: Provides a convenient interface for sending emails with various configurations (e.g., SMTP, Gmail).</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Supports various protocols: Works with SMTP, IMAP, POP3, and other mail protocols.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Flexible Configuration: Easily configure email settings (host, port, credentials, etc.) through application properties or configuration files.</p>

<p>19) byte-buddy </p>

```
<dependency>
    <groupId>net.bytebuddy</groupId>
    <artifactId>byte-buddy</artifactId>
    <version>1.14.16</version>
</dependency>
```
<p>The byte-buddy dependency provides you with the tools to dynamically work with Java bytecode. This is a powerful technique with various applications, especially in scenarios where you need to customize the behavior of classes or implement advanced features like AOP.</p>

<h4>Key Features:</h4>

<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Code Generation: Create new classes or modify existing ones without needing to write or compile Java source code directly. This is incredibly useful for: </p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • AOP (Aspect-Oriented Programming): Implement cross-cutting concerns (like logging, security) by dynamically weaving in behavior at runtime.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Dynamic Proxies: Create proxies for objects to intercept method calls and add custom logic.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Class Transformation: Modify existing classes to enhance their behavior or adapt them to specific needs.</p>

<p>20) twilio </p>

```
 <dependency>
    <groupId>com.twilio.sdk</groupId>
    <artifactId>twilio</artifactId>
   <version>8.23.0</version>
</dependency>
```
<p>The twilio dependency allows you to leverage the power of the Twilio platform within your Java applications. It provides a convenient and efficient way to implement communication features like SMS, voice calls, and more.</p>

<h4>Key Features:</h4>

<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Simplified API Interactions: The SDK abstracts away the complexities of interacting with Twilio's REST API.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Language Support: Available for various programming languages (Java, Python, Node.js, etc.).</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Easy Integration: Easily integrate Twilio functionality into your applications.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Well-Documented: Extensive documentation and examples are available to help you get started.</p>

<p>21) javax.mail </p>

```
<dependency>
    <groupId>com.sun.mail</groupId>
    <artifactId>javax.mail</artifactId>
    <version>1.6.2</version>
</dependency>
```
<p>The javax.mail dependency provides you with the necessary tools to work with email in your Java applications. It offers a standardized and robust way to handle email-related tasks.

Note: While com.sun.mail is a common implementation of the JavaMail API, other implementations might be available.</p>

<h4>Key Features:</h4>

<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Platform-Independent: Works across different operating systems and Java platforms.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Protocol Support: Supports various email protocols like SMTP, IMAP, POP3, and more.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Flexible: Allows you to customize email messages with attachments, headers, and other properties.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Well-Established: A widely used and well-supported standard API for email operations.</p>

<p>22) poi-ooxml </p>

```
<dependency>
    <groupId>org.apache.poi</groupId>
   <artifactId>poi-ooxml</artifactId>
   <version>5.2.3</version>
</dependency>
```
<p>The poi-ooxml dependency provides you with the tools to work with OOXML files (Excel, Word, PowerPoint) programmatically in Java. It's a powerful library for a wide range of use cases involving data processing and document generation.</p>

<h4>Key Features:</h4>

<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Data Processing: Read and manipulate data from Excel files for analysis, reporting, and other tasks.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Report Generation: Create dynamic reports in Excel format.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Document Automation: Generate customized Word documents or PowerPoint presentations.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • File Conversion: Convert between different file formats (e.g., Excel to CSV).</p>

<p>22) java-jwt </p>

```
<dependency>
     <groupId>com.auth0</groupId>
     <artifactId>java-jwt</artifactId>
     <version>3.18.1</version>
</dependency>
```
<p>The java-jwt dependency provides you with the necessary tools to work with JWTs in your Java applications. It simplifies the process of implementing secure and reliable authentication and authorization mechanisms.</p>

<h4>Key Features:</h4>

<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • JWT Creation: Easily create signed JWTs with claims (e.g., user ID, roles, expiration time).</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • JWT Verification: Verify the authenticity and integrity of received JWTs.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Algorithm Support: Supports various JWT signing algorithms (e.g., HS256, RS256, RSA).</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Claim Extraction: Extract claims from a JWT for use within your application.</p>

<p>23) tika-core </p>

```
<dependency>
    <groupId>org.apache.tika</groupId>
    <artifactId>tika-core</artifactId>
    <version>2.8.0</version>
</dependency>
```
<p>The tika-core dependency provides you with a robust and versatile toolkit for working with various file formats. It simplifies the process of detecting file types, extracting metadata, and extracting text content, making it a valuable tool for many data-related tasks.</p>

<h4>Key Features:</h4>

<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Supports a Wide Range of File Formats: Handles a vast number of file formats, including common office documents, images, archives, and more.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Extensible: Easily extend Tika to support new file formats through custom parsers.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Efficient: Leverages efficient parsing techniques for fast and accurate results.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Open Source: A community-driven project with a large and active user base.</p>

<p>24) spring-boot-starter-security </p>

```
<dependency>
     <groupId>org.springframework.boot</groupId>
     <artifactId>spring-boot-starter-security</artifactId>
</dependency>
```
<p>The spring-boot-starter-security dependency is essential for building secure Spring Boot applications. It provides a solid foundation for implementing authentication and authorization features, making it easier to protect your application from unauthorized access and data breaches.</p>

<h4>Key Features:</h4>

<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Spring Security Integration: Leverages the powerful Spring Security framework, providing a robust and flexible security solution.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Easy Configuration: Simplifies the process of setting up security by providing default configurations and allowing for customization.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Support for Various Authentication Mechanisms: Supports various authentication methods, including:
Username/Password: Traditional username and password-based authentication.
OAuth2: Integrate with popular OAuth2 providers (e.g., Google, Facebook, GitHub).
JWT: Implement token-based authentication using JSON Web Tokens.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Support for Authorization: Implement role-based access control (RBAC), attribute-based access control (ABAC), and other authorization mechanisms.</p>

<p>25) tika-parsers-standard-package </p>

```
<dependency>
    <groupId>org.apache.tika</groupId>
    <artifactId>tika-parsers-standard-package</artifactId>
    <version>2.8.0</version>
</dependency>
```
<p>The tika-parsers-standard-package dependency enhances the capabilities of the Apache Tika library by providing a collection of pre-built parsers for common file formats. This simplifies the process of working with various file types and improves the overall efficiency of your Tika-based applications.</p>

<h4>Key Features:</h4>

<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Enhanced Functionality: Adds support for a large number of file formats beyond the basic capabilities of the tika-core library.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Convenience: Provides ready-to-use parsers, saving you the effort of developing custom parsers for common file types.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Improved Performance: Often includes optimized parsers for specific file formats, leading to faster processing.</p>

<p>26) jjwt </p>

```
<dependency>
     <groupId>io.jsonwebtoken</groupId>
     <artifactId>jjwt</artifactId>
     <version>0.9.1</version>
</dependency>
```
<p>The jjwt dependency provides you with the necessary tools to work with JWTs in your Java applications. It simplifies the process of implementing secure and reliable authentication and authorization mechanisms.</p>

<h4>Key Features:</h4>

<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • JWT Creation: Easily create signed JWTs with claims (e.g., user ID, roles, expiration time).</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • JWT Verification: Verify the authenticity and integrity of received JWTs.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Algorithm Support: Supports various JWT signing algorithms (e.g., HS256, RS256, RSA).</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Claim Extraction: Extract claims from a JWT for use within your application.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Easy to Use: Provides a simple and intuitive API for working with JWTs.</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp • Authentication: Implement user authentication and authorization within your applications.</p>











































  










