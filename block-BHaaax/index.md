<!-- 
### Exercise 1

1. Create a simple page having a header, main content, and a footer.

2. Inside the header keep the brand name to the left and all the navigation to the right.

3. Inside the main content take an article section having two columns. In the first column put a heading and some introductory text of the article and in the second column take an image. -->


<!---HTML CSSS--->


<!DOCTYPE html>
<html lang="eng">
  <head>
      <meta charset="UTF-8">
      <title> positioning content</title>
      <link rel="stylesheet" href="stylesheet/style.css">
  </head>
  <body>
      <header class="head">
          <div class="container clearfix">
              <a class="logo"href="#" > NETPAYSHOP </a>
              <nav class="nav">
                 <a href="#">Home</a>
                 <a href="#">Profile</a>
                 <a href="#">Blog</a>
              </nav>
          </div>
              
      </header>
      <main>
        <section>
            <article class="article">
               <div class="container">
                   <h1> DUMMY TEXT </h1>
                  <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Eum ducimus
                     nemo quasi assumenda est? Quidem numquam aperiam dolores exercitationem,
                     quibusdam nam repudiandae deserunt repellendus sit at illo perspiciatis
                     accusamus similique.
                  </p>

                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta maxime
                     ad consequuntur, esse, maiores natus repellendus velit sit quas ipsam 
                     eaque! Iste, unde consequatur at id non voluptas ullam optio.
                  </p> 
            
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit nemo vero
                     hic voluptate velit magni, sapiente fugit mollitia nesciunt quia tenetur,
                     expedita quasi sequi assumenda, neque recusandae deleniti culpa! Beatae!
                  </p>

                  <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Necessitatibus
                     laudantium quod temporibus. Voluptates tempore quam vero nobis officiis
                     repudiandae necessitatibus provident! Asperiores, laboriosam nostrum
                     repudiandae a blanditiis magni? Quibusdam, voluptatem. 
                  </p> 
                 
                  <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Necessitatibus 
                     laudantium quod temporibus. Voluptates tempore temporibus. Voluptates
                     tempore quam vero nobis officiis repudiandae necessitatibus
                  </p>
                 
        </section>
            </article>
               </div>
               <section>
                    <article class="article-2">
                       <div class=" container clearfix">
                          <img src="../position/media/pic-01.jpg"  alt="Loading error">
                        </div>
                    </article>
               </section>

      </main>
      <footer class="foot ">
         <div class="container">
             <small> &copy; ALT CAMPUS</small>
         </div>
      </footer>
  </body>
</html>