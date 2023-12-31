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

