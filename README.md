**Spring Data JPA**

**JPA Annotations @Table, @Column, @GeneratedValue, @UniqueConstraint**

**Primary key generation strategies AUTO, IDENTITY, SEQUENCE and TABLE**

**Use Hibernate @CreationTimestamp and @UpdateTimestamp & Add Lombok**

    @CreationTimestamp
    private LocalDateTime dateCreated;
    @UpdateTimestamp
    private LocalDateTime lastUpdateed;

**Add Lombok**

Project Lombok is a java library that automatically plugs into your editor and build tools, spicing up your java.
Never write another getter or equals method again, with one annotation your class has a fully featured builder, Automate your logging variables, and much more.

  @Entity
  @Setter
  @Getter
  @NoArgsConstructor
  @AllArgsConstructor
  @Table(name ="products")
  public class Product {

  //remove all Setter and Geeter and Constructor in the class 
  
  }

**Understanding important Repository Interfaces and It’s Hierarchy**
![Screenshot 2023-12-31 at 10 27 01 AM](https://github.com/ranaNarin/SpringDataJPA_POC/assets/13502470/9b9ea69c-11ea-4add-b141-6b47547377d7)

![Screenshot 2023-12-31 at 10 28 12 AM](https://github.com/ranaNarin/SpringDataJPA_POC/assets/13502470/20fb2609-9729-45c4-a821-5f73c27504dd)

![Screenshot 2023-12-31 at 10 31 29 AM](https://github.com/ranaNarin/SpringDataJPA_POC/assets/13502470/15a705d7-0aea-478b-b7f5-88982cdc2188)

![Screenshot 2023-12-31 at 10 47 50 AM](https://github.com/ranaNarin/SpringDataJPA_POC/assets/13502470/2330954d-b375-4863-8acc-dcdf03fcea2a)

![Screenshot 2023-12-31 at 10 48 28 AM](https://github.com/ranaNarin/SpringDataJPA_POC/assets/13502470/458b2b5f-2093-4cb7-bbec-49f79a94ff2e)

![Screenshot 2023-12-31 at 10 49 31 AM](https://github.com/ranaNarin/SpringDataJPA_POC/assets/13502470/11ba6e3d-2c01-4a84-8bbc-0f905cc47af8)

![Screenshot 2023-12-31 at 10 49 57 AM](https://github.com/ranaNarin/SpringDataJPA_POC/assets/13502470/f29dbcfb-7503-423b-a039-a7e9244805e5)






