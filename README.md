- 👋 Hi, I’m @PhamXuanTuanAnh
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ... le;qưleq
jlkjlk

    @Override
    protected void doGet(HttpServletRequest req, HttpServletResponse resp) throws ServletException, IOException {
        resp.setContentType("text/html");
        resp.getWriter().println(
            "<html><body>" +
            "<form method='POST'>" +
            "<label>Enter number of rectangles:</label>" +
            "<input type='text' name='number'>" +
            "<input type='submit' value='Submit'>" +
            "</form></body></html>"
        );
}
