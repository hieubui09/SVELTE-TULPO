<script>
    //khai báo
    window.scroll(0, 0);
    function scrollDown(x, y) {
        document.querySelector(".container__main").style.top = -x * 100 + "vh";
        document.querySelector(".lighthouse").style.backgroundPosition =
            "100% " + x * 30 + "%";
        document.querySelector(".lighthouse").style.transition = "2s";
    }
    function scrollUp(x, y) {
        document.querySelector(".container__main").style.top =
            -(y - 1) * 100 + "vh";
        document.querySelector(".lighthouse").style.backgroundPosition =
            "100% " + (y - 1) * 30 + "%";
    }
</script>

<main>
    <section>
        <div class="lighthouse">
            <div class="animation">
                <div class="animation__item">
                    <img src="images/Group.png" alt="" />
                </div>
            </div>
            <div class="animation__t" />
            <div class="container__main">
                <div
                    class="content__one"
                    on:mousewheel={(value) => {
                        if (value.deltaY > 0) {
                            scrollDown(1, 2);
                        }
                    }}
                >
                    <div class="container">
                        <h1>CON ĐƯỜNG ĐẾN VỚI</h1>
                        <h2>LẬP TRÌNH FINTECH</h2>
                        
                            <h3>Câu chuyện của chúng tôi</h3>
                           
                       
                        <p>
                            Chào bạn, bạn có phải là một tín đồ của Bitcoin và
                            theo dõi nó trên từng bước biến chuyển? Có bao giờ
                            bạn cảm thấy Bitcoin thật giàu tiềm năng và bí ẩn
                            nhưng cũng đầy những rủi ro đáng lo?
                        </p>
                        <p>
                            Câu chuyện của Tulpo Software bắt đầu từ những bất
                            ngờ đó...
                        </p>
                        <p>
                            Chúng tôi cũng từng như vậy, vô tình biết đến
                            Bitcoin và đồng tiền này đã mang lại quá nhiều bất
                            ngờ mà chính chúng tôi cũng không dám nghĩ đến.
                        </p>
                        <div>
                            <img src="images/moue.png" alt="" />
                            <span>Cuộn để xem tiếp</span>
                        </div>
                    </div>
                </div>
                <div
                    class="content__two"
                    on:mousewheel={(value) => {
                        if (value.deltaY > 0) {
                            scrollDown(2, 3);
                        } else {
                            scrollUp(2, 1);
                        }
                    }}
                >
                    <div class="container">
                        <p>
                            Khi đó, tôi chỉ là một game thủ nghiệp dư chân ướt
                            chân ráo bước vào cộng đồng game Việt Nam.
                        </p>
                        <p>
                            Việc tôi làm hàng ngày chỉ đơn giản là mua thẻ điện
                            thoại để nạp tiền vào game. Tình cờ vào một ngày,
                            tôi nhận được 500 mã có tên BTC. Tất nhiên ở thời
                            điểm ấy, BTC chưa có nhiều dấu ấn trên thị trường
                            cũng như không được đánh giá cao bởi các nhà kinh tế
                            học, nên trong đầu của một chàng trai mới lớn ham
                            chơi game thì những mã thông báo ấy chẳng có chút ý
                            nghĩ gì.
                        </p>
                        <p>
                            Điều khiến tôi phải suy nghĩ chỉ đơn giản là: làm
                            sao để trốn đi chơi game cùng bạn mà bố mẹ không
                            biết?
                        </p>
                        <div>
                            <img src="images/moue.png" alt="" />
                            <span>Cuộn để xem tiếp</span>
                        </div>
                    </div>
                </div>
                <div
                    class="content__three"
                    on:mousewheel={(value) => {
                        if (value.deltaY > 0) {
                            scrollDown(3, 4);
                        } else {
                            scrollUp(3, 2);
                        }
                    }}
                >
                    <div class="container">
                        <p>
                            Thời gian trôi nhanh, khi những năm tháng học trò
                            hồn nhiên kết thúc cũng là lúc tôi bước chân vào
                            giảng đường đại học. Tôi quay cuồng trong một thế
                            giới mới, vừa khao khát khám phá vừa ngập ngừng lạ
                            lẫm. Tôi tiêu xài hoang phí sức lức và tiền bạc của
                            mình vào những bữa tiệc vỉa hè và những chuyến đi
                            xuyên đêm không biết điểm dừng. Tôi rong ruổi và tự
                            do làm chính mình. Nhưng rồi, tôi nhận quả đắng đầu
                            đời: học lại. Tôi bắt đầu chỉnh đốn lại bản thân,
                            tập trung học lại nhưng trong đầu lại quanh quẩn suy
                            nghĩ "Cần phải làm một điều gì khác". Tôi không muốn
                            để tuổi trẻ của mình trôi qua lãng phí với những
                            tiết học nhàm chán trên trường.
                        </p>
                        <p>
                            Dù theo học chuyên ngành kỹ thuật cơ điện tử nhưng
                            tôi lại thử thách bản thân ở một lĩnh vực khác - trở
                            thành một nhân viên sale ngày ngày đi thuyết trình
                            sản phẩm đến khô cả họng. Nhưng mọi thứ chưa bao giờ
                            là dễ dàng. Học tập đi xuống và công việc cũng chẳng
                            mấy khả quan khiến tôi nghi ngờ vào khả năng của
                            chính mình. Giữa lúc bế tắc, tôi được mời gọi đầu tư
                            Ethereum - đồng tiền kỹ thuật số đứng thứ 2 trên thị
                            trường hiện tại. Tôi bắt đầu tìm hiểu về tiền kĩ
                            thuật số, về blockchain, về thị trường crypto chợt
                            nhớ ra mình đã từng được nhận 500 BTC. Tôi lục lọi
                            lại tài liệu cũ kĩ và may mắn là tìm lại được. Tôi
                            đã dành số tiền ấy để đầu tư vào ETH và chính thức
                            bước vào thế giới tiền ảo.
                        </p>
                        <div>
                            <img src="images/moue.png" alt="" />
                            <span>Cuộn để xem tiếp</span>
                        </div>
                    </div>
                </div>
                <div
                    class="content__four"
                    on:mousewheel={(value) => {
                        if (value.deltaY < 0) {
                            scrollUp(4, 3);
                        }
                    }}
                >
                    <div class="container">
                        <p>
                            Đó là câu chuyện của chúng tôi, cách mà Tulpo
                            Software được hình thành. Trải qua nhiều thăng trầm,
                            có lúc chúng tôi nghĩ rằng mình đã lạc hướng khi
                            phải đối diện với những thất bại, nhưng niềm tin vào
                            tiềm năng tương lai của Bitcoin và Blockchain đã
                            giúp chúng tôi giữ vựng lập trường kiên định của
                            mình. Tôi tìm được những đồng đội tốt cùng chung lý
                            tưởng, chúng tôi tìm được hướng đi cho Tulpo, đó là
                            trở thành những lập trình viên đúng nghĩa đưa
                            blockchain đến gần hơn với người Việt. Chúng tôi
                            mong muốn blockchain sẽ mang đến những giải pháp
                            tuyệt vời cho doanh nghiệp, khai sáng tư duy công
                            nghệ của những nhà phát triển phần mềm như cách nó
                            đã mở ra nhiều điều trong bộ não hạn hẹp của chúng
                            tôi. Blockchain cũng giúp chúng tôi- TulPo Software
                            có chỗ đứng trên thị trường theo triết lý làm việc
                            TRI THỨC - BỀN BỈ - TRÁCH NHIỆM.
                        </p>
                        <p>
                            Có lẽ câu chuyện cho một cái kết hiện tại sẽ dài hơn
                            là những gì bạn đọc được nhưng tôi xin phép dừng ở
                            đây. Và đến thời điểm hiện tại, với các dịch vụ
                            chúng tôi cung cấp cho người dùng như một điều gì đó
                            khẳng định niềm tin của chúng tôi với thị trường và
                            tinh thần làm việc theo triết lý chung.
                        </p>
                        <div>
                            <img src="images/moue.png" alt="" />
                            <span>Cuộn để xem tiếp</span>
                        </div>
                    </div>
                </div>
            </div>
            <div class="container__tab">
                <div class="content__one"  on:mousewheel={(value) => {
                    if (value.deltaY > 0) {
                        scrollDown(1, 2);
                    }
                }}>
                    <div class="container">
                        <h1>CON ĐƯỜNG ĐẾN VỚI</h1>
                        <h2>LẬP TRÌNH FINTECH</h2>
                        <div>
                            <h3>Câu chuyện của chúng tôi</h3>
                            <img src="images/Vet.png" alt="" />
                        </div>
                        <p>
                            Chào bạn, bạn có phải là một tín đồ của Bitcoin và
                            theo dõi nó trên từng bước biến chuyển? Có bao giờ
                            bạn cảm thấy Bitcoin thật giàu tiềm năng và bí ẩn
                            nhưng cũng đầy những rủi ro đáng lo?
                        </p>
                        <p>
                            Câu chuyện của Tulpo Software bắt đầu từ những bất
                            ngờ đó...
                        </p>
                        <p>
                            Chúng tôi cũng từng như vậy, vô tình biết đến
                            Bitcoin và đồng tiền này đã mang lại quá nhiều bất
                            ngờ mà chính chúng tôi cũng không dám nghĩ đến.
                        </p>
                        
                    </div>
                </div>
                <div class="content__two"   on:mousewheel={(value) => {
                    if (value.deltaY > 0) {
                        scrollDown(2, 3);
                    } else {
                        scrollUp(2, 1);
                    }
                }}>
                    <div class="container">
                        <p>
                            Khi đó, tôi chỉ là một game thủ nghiệp dư chân ướt
                            chân ráo bước vào cộng đồng game Việt Nam.
                        </p>
                        <p>
                            Việc tôi làm hàng ngày chỉ đơn giản là mua thẻ điện
                            thoại để nạp tiền vào game. Tình cờ vào một ngày,
                            tôi nhận được 500 mã có tên BTC. Tất nhiên ở thời
                            điểm ấy, BTC chưa có nhiều dấu ấn trên thị trường
                            cũng như không được đánh giá cao bởi các nhà kinh tế
                            học, nên trong đầu của một chàng trai mới lớn ham
                            chơi game thì những mã thông báo ấy chẳng có chút ý
                            nghĩ gì.
                        </p>
                        <p>
                            Điều khiến tôi phải suy nghĩ chỉ đơn giản là: làm
                            sao để trốn đi chơi game cùng bạn mà bố mẹ không
                            biết?
                        </p>
                        <div>
                            <img src="images/moue.png" alt="" />
                            <span>Cuộn để xem tiếp</span>
                        </div>
                    </div>
                </div>
                <div class="content__three"     on:mousewheel={(value) => {
                    if (value.deltaY > 0) {
                        scrollDown(3, 4);
                    } else {
                        scrollUp(3, 2);
                    }
                }}>
                    <div class="container">
                        <p>
                            Thời gian trôi nhanh, khi những năm tháng học trò
                            hồn nhiên kết thúc cũng là lúc tôi bước chân vào
                            giảng đường đại học. Tôi quay cuồng trong một thế
                            giới mới, vừa khao khát khám phá vừa ngập ngừng lạ
                            lẫm. Tôi tiêu xài hoang phí sức lức và tiền bạc của
                            mình vào những bữa tiệc vỉa hè và những chuyến đi
                            xuyên đêm không biết điểm dừng. Tôi rong ruổi và tự
                            do làm chính mình. Nhưng rồi, tôi nhận quả đắng đầu
                            đời: học lại. Tôi bắt đầu chỉnh đốn lại bản thân,
                            tập trung học lại nhưng trong đầu lại quanh quẩn suy
                            nghĩ "Cần phải làm một điều gì khác". Tôi không muốn
                            để tuổi trẻ của mình trôi qua lãng phí với những
                            tiết học nhàm chán trên trường.
                        </p>
                        <p>
                            Dù theo học chuyên ngành kỹ thuật cơ điện tử nhưng
                            tôi lại thử thách bản thân ở một lĩnh vực khác - trở
                            thành một nhân viên sale ngày ngày đi thuyết trình
                            sản phẩm đến khô cả họng. Nhưng mọi thứ chưa bao giờ
                            là dễ dàng. Học tập đi xuống và công việc cũng chẳng
                            mấy khả quan khiến tôi nghi ngờ vào khả năng của
                            chính mình. Giữa lúc bế tắc, tôi được mời gọi đầu tư
                            Ethereum - đồng tiền kỹ thuật số đứng thứ 2 trên thị
                            trường hiện tại. Tôi bắt đầu tìm hiểu về tiền kĩ
                            thuật số, về blockchain, về thị trường crypto chợt
                            nhớ ra mình đã từng được nhận 500 BTC. Tôi lục lọi
                            lại tài liệu cũ kĩ và may mắn là tìm lại được. Tôi
                            đã dành số tiền ấy để đầu tư vào ETH và chính thức
                            bước vào thế giới tiền ảo.
                        </p>
                        <div>
                            <img src="images/moue.png" alt="" />
                            <span>Cuộn để xem tiếp</span>
                        </div>
                    </div>
                </div>
                <div class="content__four"   on:mousewheel={(value) => {
                    if (value.deltaY < 0) {
                        scrollUp(4, 3);
                    }
                }}>
                    <div class="container">
                        <p>
                            Đó là câu chuyện của chúng tôi, cách mà Tulpo
                            Software được hình thành. Trải qua nhiều thăng trầm,
                            có lúc chúng tôi nghĩ rằng mình đã lạc hướng khi
                            phải đối diện với những thất bại, nhưng niềm tin vào
                            tiềm năng tương lai của Bitcoin và Blockchain đã
                            giúp chúng tôi giữ vựng lập trường kiên định của
                            mình. Tôi tìm được những đồng đội tốt cùng chung lý
                            tưởng, chúng tôi tìm được hướng đi cho Tulpo, đó là
                            trở thành những lập trình viên đúng nghĩa đưa
                            blockchain đến gần hơn với người Việt. Chúng tôi
                            mong muốn blockchain sẽ mang đến những giải pháp
                            tuyệt vời cho doanh nghiệp, khai sáng tư duy công
                            nghệ của những nhà phát triển phần mềm như cách nó
                            đã mở ra nhiều điều trong bộ não hạn hẹp của chúng
                            tôi. Blockchain cũng giúp chúng tôi- TulPo Software
                            có chỗ đứng trên thị trường theo triết lý làm việc
                            TRI THỨC - BỀN BỈ - TRÁCH NHIỆM.
                        </p>
                        <p>
                            Có lẽ câu chuyện cho một cái kết hiện tại sẽ dài hơn
                            là những gì bạn đọc được nhưng tôi xin phép dừng ở
                            đây. Và đến thời điểm hiện tại, với các dịch vụ
                            chúng tôi cung cấp cho người dùng như một điều gì đó
                            khẳng định niềm tin của chúng tôi với thị trường và
                            tinh thần làm việc theo triết lý chung.
                        </p>
                        <div>
                            <img src="images/moue.png" alt="" />
                            <span>Cuộn để xem tiếp</span>
                        </div>
                    </div>
                </div>
            </div>
            <div class="container__mobi">
                <div class="container--mobi--text">
                    <h1>CON ĐƯỜNG ĐẾN VỚI</h1>
                    <h2>LẬP TRÌNH FINTECH</h2>
                    <div>
                        <h3>Câu chuyện của chúng tôi</h3>
                        <img src="images/Vet.png" alt="" />
                    </div>
                    
                     <p>
                        Chào bạn, bạn có phải là một tín đồ của Bitcoin và theo
                        dõi nó trên từng bước biến chuyển? Có bao giờ bạn cảm
                        thấy Bitcoin thật giàu tiềm năng và bí ẩn nhưng cũng đầy
                        những rủi ro đáng lo?
                    </p>
                    <p>
                        Câu chuyện của Tulpo Software bắt đầu từ những bất ngờ
                        đó...
                    </p>
                    <p>
                        Chúng tôi cũng từng như vậy, vô tình biết đến Bitcoin và
                        đồng tiền này đã mang lại quá nhiều bất ngờ mà chính
                        chúng tôi cũng không dám nghĩ đến.
                    </p>
                    <p>
                        Khi đó, tôi chỉ là một game thủ nghiệp dư chân ướt chân
                        ráo bước vào cộng đồng game Việt Nam. Việc tôi làm hàng
                        ngày chỉ đơn giản là mua thẻ điện thoại để nạp tiền vào
                        game. Tình cờ vào một ngày, tôi nhận được 500 mã có tên
                        BTC. Tất nhiên ở thời điểm ấy, BTC chưa có nhiều dấu ấn
                        trên thị trường cũng như không được đánh giá cao bởi các
                        nhà kinh tế học, nên trong đầu của một chàng trai mới
                        lớn ham chơi game thì những mã thông báo ấy chẳng có
                        chút ý nghĩ gì. Điều khiến tôi phải suy nghĩ chỉ đơn
                        giản là: làm sao để trốn đi chơi game cùng bạn mà bố mẹ
                        không biết?
                    </p>
                    <p>
                        Thời gian trôi nhanh, khi những năm tháng học trò hồn
                        nhiên kết thúc cũng là lúc tôi bước chân vào giảng đường
                        đại học. Tôi quay cuồng trong một thế giới mới, vừa khao
                        khát khám phá vừa ngập ngừng lạ lẫm. Tôi tiêu xài hoang
                        phí sức lức và tiền bạc của mình vào những bữa tiệc vỉa
                        hè và những chuyến đi xuyên đêm không biết điểm dừng.
                        Tôi rong ruổi và tự do làm chính mình. Nhưng rồi, tôi
                        nhận quả đắng đầu đời: học lại. Tôi bắt đầu chỉnh đốn
                        lại bản thân, tập trung học lại nhưng trong đầu lại
                        quanh quẩn suy nghĩ "Cần phải làm một điều gì khác". Tôi
                        không muốn để tuổi trẻ của mình trôi qua lãng phí với
                        những tiết học nhàm chán trên trường. Dù theo học chuyên
                        ngành kỹ thuật cơ điện tử nhưng tôi lại thử thách bản
                        thân ở một lĩnh vực khác - trở thành một nhân viên sale
                        ngày ngày đi thuyết trình sản phẩm đến khô cả họng.
                        Nhưng mọi thứ chưa bao giờ là dễ dàng. Học tập đi xuống
                        và công việc cũng chẳng mấy khả quan khiến tôi nghi ngờ
                        vào khả năng của chính mình. Giữa lúc bế tắc, tôi được
                        mời gọi đầu tư Ethereum - đồng tiền kỹ thuật số đứng thứ
                        2 trên thị trường hiện tại. Tôi bắt đầu tìm hiểu về tiền
                        kĩ thuật số, về blockchain, về thị trường crypto chợt
                        nhớ ra mình đã từng được nhận 500 BTC. Tôi lục lọi lại
                        tài liệu cũ kĩ và may mắn là tìm lại được. Tôi đã dành
                        số tiền ấy để đầu tư vào ETH và chính thức bước vào thế
                        giới tiền ảo.
                    </p>
                
                   
                </div>
            </div>
        </div>
    </section>
</main>

<style lang="scss">
    @import "../scss/main.scss";
</style>
