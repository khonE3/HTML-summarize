# HTML-summarize
All commands HTML

## 🚀 Fisrt Open and Run basic.HTML
Open and run file --->basic.HTML


## Usage/Examples

```

    <!-- Basic Tag -->  

    <a href="#" target="_blank">click here</a>

    <!-- Keyลัดcommentคือ Ctrl+/ -->
    <h1>H1</h1> <!--ขนาดตัวใหญ่1ถึง6-->
    <s>ขีดเส้นใต้Text</s>
    <br> <!--ขึ้นบรรทัดใหม่เลย-->
    <p>ข้อความปกติ</p> <!--Paragraph-->
    <br>
    <b>ตัวหนา</b> <!--Bold Text-->
    <br>
    <i>ตัวเอียง</i> <!--Italic Text-->
    <br>
    <strong>ตัวหนาStrong</strong> <!--Strong Text-->
    <br>
    <em>ตัวเอียงEmphasized</em> <!--Emphasized Text-->
    <br>
    <mark>สีmarkคล้ายhighlight</mark> <!--Marked Text-->
    <br>
    <small>ตัวเล็กลง</small> <!--Small Text-->
    <br>
    <del>ตัวขีดค่าText</del> <!--Delete Text-->
    <br>
    <ins>ขีดเส้นใต้Text</ins> <!--Inserted Text-->
    <br>
    <sub>ตัวห้อย</sub> <!--Subscript Text-->
    <sup>ตัวข้างบน</sup> <!--Superscript Text-->
    <br>

    <hr> <!--ขึ้นบรรทัดใหม่โดยมีเส้นคั่น-->

    
    <!-- การใส่LINK -->

    <h2><ins>Link</ins></h2>
    <a href="https://translate.google.com/?sl=en&tl=th&text=Inserted&op=translate">Go to translate</a> <!--เปลี่ยนหน้าเว็บในแท็บเดิม-->
    <br>
    <br>
    <a href="https://translate.google.com/?sl=en&tl=th&text=Inserted&op=translate" target="_blank">New tab to translate</a> 
    <!--เปลี่ยนหน้าเว็บในแท็บใหม่--> 
    <br>
    <hr>



    <!-- การใส่รูป -->

    <h2><i>images</i></h2>
    <img src="https://play-lh.googleusercontent.com/RZ5luCUwc5QtJP9xDn-ZCwEutT160GVyoh5K1eu4YJ5fD7v4LP5ptVdgR9mz4Hnr7A" alt="รูปgoogle">
    <!--ใส่รูปภาพ-->
    <br>
    <br>
    <h2><b>images link</b></h2>
    <a title="go to translate" href="https://translate.google.com/" target="_blank"> <!--<a title="go" hold cursor เพื่อดูข้อความ-->
        <img src="https://images.droidsans.com/wp-content/uploads/2019/09/cover-ok-google.jpg" alt="รูปลุง"></a>
    <!--กดรูปภาพเพื่อไปแท็บใหม่-->
    <br>
    <hr>



    <!-- ตาราง -->

    <h1><ins>Table</ins></h1>
    <img src="Screenshot 2022-02-09 231617.png" alt="" width="300px" height="200px">

    <table>
        <thead>
                <tr> <!--กำหนดแถว Table row-->
                    <th>First name</th> <!--Table Head กำหนดคอลัมน์ในส่วนหัว-->
                    <th>Last name</th> <!--กด Shift+Alt+ลูกศรลงเพื่อกอปโค้ดทั้งหมด-->
                    <th>Age name</th>
                </tr>

                <tr>
                    <td>Thanakrit</td> <!--Table Data ไว้ใส่ข้อมูลต่างๆ-->
                    <td>Thuakthao</td> <!--กด Ctral+D เพื่อกอปText-->
                    <td>19</td>
                </tr>
        </thead>        
    </table>
    <hr>
    




    <!-- การทำList -->

    <h2><mark>List ul</mark></h2>

    <ul type="circle"> <!--มี biullet ตัวจุด-->
        <li>fox1</li><!--List-->
        <li>fox2</li>
    </ul>

        <!-- (ul) list-style-type:
    list-style-type: disc; = จุดbullet
    list-style-type: circle; = วงกลมโปร่ง
    list-style-type: square; = สี่เหลี่ยม
    -->


    <h2><mark>List ol</mark></h2>

    <ol> <!--มีหมายเลขกำกับ 1. 2. 3.-->
        <li>dog</li>
        <li>dog</li>
    </ol>
    <br>
    <hr>
    
    <!-- ol Type 
    Type A = A B C 
    Type a = a b c
    Type I = I II III -->



    <!-- การทำForm -->

    <h3><mark>Form</mark></h3>
    <form>
        <fieldset> <!--ขอบเส้น-->
            <legend> <!--ส่วนบนtitle-->
                Register Form
            </legend>

            <label for="firstname">Firstname</label> <!-- lable = ป้ายกำกับ -->
            <input type="text" placeholder="Enter your firstname"> <!-- ข้อความในinput -->
            <br>
            <label for="lastname">Lastname</label>
            <input type="text" placeholder="Enter your lastname">
            <br>
            <label for="gender">Select Gender</label>
            <input type="radio" name="gender" value="male" checked>Male <!--เลือกได้checkเดียว-->
            <input type="radio" name="gender" value="female">Female
            <br>
            <input type="checkbox" value="value1" name="value1">ชายแกร่ง <!--checkได้หลายตัว-->
            <input type="checkbox" value="value2" name="value2">ชายอ่อน
            <input type="checkbox" value="value3" name="value3">ชายสมชาย
            <br>
            <input type="submit" value="Submit"> <!--ปุ่มกดsubmit-->
            <a href="formbasic.html" target="_blank">More</a>
            <br> 
        </fieldset>
    </form>
    <br>
    <hr>



    <!-- Block and Inline Element -->

    <h3><b>Block element and Inline element</b></h3>
    <img src="Screenshot 2022-02-09 185358.png" alt="">
    <br>
    <hr>

    <h2><i>div</i></h2>
    <div class="box"> <!--div คือ new element-->
        <h4>box1</h4>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
    </div>
    <div class="box center"> <!-- multi class-->
        <h4>box1</h4>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing..</p>
    </div>
    <div class="box"> <!--class ใช้ element ได้หลายตัว-->
        <h4>box1</h4>
        <p>Lorem ipsum dolor sit amet consectetur..</p>
    </div>
    <br>
    <br>
    <hr>


    <!-- ID -->

    <h3>ID</h3> <!--ID ใช้ element ได้ตัวเดียว-->
    <div id="MyID">Only ID</div>
    <br>
    <br>
    <hr>


    <!-- iFrame -->

    <h1>iframe</h1> <!--แสดงหน้าเว็บอื่นในเว็บเดิม-->
    <iframe width="560" height="315" src="https://www.youtube.com/embed/7MeQxBqchNU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    <br>
    <iframe src="if.html" frameborder="1" width="1500px" height="400px"></iframe>
    <br>
    <hr>


    <!-- Entities -->

    <h1>HTML Entities</h1> <!--แสดงข้อความเฉพาะให้แสดงบนหน้าเว็บได้-->
    <img src="Screenshot 2022-02-09 222104.png" alt="">
    <p>This is &lt &gt</p>
    <br>
    <hr>


    <!-- Sematic -->

    <h2><mark>Sematics element</mark></h2> <!--Tag ที่มีความหมายในตัว-->
    <img src="Screenshot 2022-02-09 223007.png" alt="">

    <header> <!--ส่วนหัว-->
        Header
    </header>
    <nav> <!--Navigation เมนู นำทาง-->
        Nav
    </nav>
    <section> <!--Tag ใส่ข้อมูลต่างๆ-->
        Section
    </section>
    <aside> <!--sidebar เป็นเมนูด้านข้าง-->
        Aside
    </aside>
    <footer> <!--ส่วนท้าย-->
        Footer
    </footer>
    <br>
    <iframe src="Samatics.html" frameborder="1" width="1000px" height="411px"></iframe>
    <hr>
    

    <!-- Play Video and Audio -->

    <video controls>
        <source src="#" type="vidio/mp4">
    </video>

    <audio controls autoplay>
        <source src="#" type="audio/mp3">
    </audio>


```

