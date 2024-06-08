public class Car {
    private String licensePlate;
    private String make;
    private String model;
    private int year;
    private boolean isRented;

    public Car(String licensePlate, String make, String model, int year) {
        this.licensePlate = licensePlate;
        this.make = make;
        this.model = model;
        this.year = year;
        this.isRented = false;
    }

    public String getLicensePlate() { return licensePlate; }
    public String getMake() { return make; }
    public String getModel() { return model; }
    public int getYear() { return year; }
    public boolean isRented() { return isRented; }

    public void rent() { this.isRented = true; }
    public void returnCar() { this.isRented = false; }

    @Override
    public …
