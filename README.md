import { Card, CardContent } from "@/components/ui/card"; import { Button } from "@/components/ui/button"; import { Input } from "@/components/ui/input";

export default function AkniwaCoaching() { return ( <div className="p-6 space-y-12 max-w-5xl mx-auto"> {/* Home Section */} <section className="text-center space-y-4"> <img src="/path/to/akniwa-logo.png" alt="Akniwa Coaching Logo" className="mx-auto w-32" /> <h1 className="text-4xl font-bold">Akniwa Coaching Classes</h1> <p className="text-lg text-gray-600">Empowering Students for a Better Tomorrow</p> <Button>Enroll Now</Button> </section>

{/* About Section */}
  <section className="space-y-2">
    <h2 className="text-2xl font-semibold">About Us</h2>
    <p>
      At Akniwa Coaching Classes, we focus on quality education, experienced faculty,
      and personalized attention. Our goal is to help every student excel.
    </p>
  </section>

  {/* Courses Section */}
  <section className="space-y-4">
    <h2 className="text-2xl font-semibold">Our Courses</h2>
    <p>We offer classes from 8th to 12th grade in core science subjects.</p>
    <div className="grid grid-cols-1 md:grid-cols-2 gap-4">
      <Card>
        <CardContent className="p-4">
          <h3 className="font-bold text-xl">Chemistry</h3>
          <p>Instructor: Yuvraj Singh Yadav<br />Complete syllabus coverage with practical insights.</p>
        </CardContent>
      </Card>
      <Card>
        <CardContent className="p-4">
          <h3 className="font-bold text-xl">Mathematics</h3>
          <p>Instructor: Aziz Khan<br />Focus on concept clarity, speed, and accuracy.</p>
        </CardContent>
      </Card>
      <Card>
        <CardContent className="p-4">
          <h3 className="font-bold text-xl">Physics</h3>
          <p>Instructor: Vishwas Jain<br />Conceptual and problem-solving approach to learning physics.</p>
        </CardContent>
      </Card>
      <Card>
        <CardContent className="p-4">
          <h3 className="font-bold text-xl">Biology</h3>
          <p>Instructor: Deepti Nigam<br />Interactive classes with detailed diagrams and explanations.</p>
        </CardContent>
      </Card>
    </div>
  </section>

  {/* Testimonials Section */}
  <section className="space-y-2">
    <h2 className="text-2xl font-semibold">What Our Students Say</h2>
    <blockquote className="italic">"The teachers are amazing and I scored top marks thanks to Akniwa!"</blockquote>
  </section>

  {/* Contact Section */}
  <section className="space-y-2">
    <h2 className="text-2xl font-semibold">Contact Us</h2>
    <form className="space-y-2 max-w-md">
      <Input placeholder="Your Name" />
      <Input placeholder="Your Email" type="email" />
      <Input placeholder="Your Message" />
      <Button type="submit">Send Message</Button>
    </form>
  </section>
</div>

); }

